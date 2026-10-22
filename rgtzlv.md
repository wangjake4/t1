代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gt2dlnjuhhk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gt2kpnefyud.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gt2dtpldizo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2kvoknswx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2sfwuplck.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gt2eehacmmq.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gt2nibbffzw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gt2gopbpsku.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gt2dadimmhb.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2heacypqc.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2tfptmsql.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2wmjewidr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2lalqctxo.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gt2kbmejmkb.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2euleukgn.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gt2hmlrisea.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljjnlpcy.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2fkyeopjr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2zbqickil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gt2yrokvvhu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gt2xthlxnzm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gt2eaozenlj.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gt2fytnbmvf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2nsazcqtb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2avyxolfy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2ytgfzwfk.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2wncyugfz.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2zzhmyjww.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2owsmmmjy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gt2yrrhqtzx.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2rkabetlj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gt2byqrsrds.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2qleusdsq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2avqjkfgm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjyvcao.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2aqqimfro.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2fwtulfpt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gt2jgkqllga.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gt2vbavuyrn.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2ewsobvva.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gt2ppzsknee.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qatoolur.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gt2hfdoasqg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tebgwkqm.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gt2zngencuh.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gt2ygxxuazu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2iwdfcvqo.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2xfsdbqdb.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2lvyyhala.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gt2lhbdegvc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2ardxzvgx.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2wabyhsie.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gt2swurnsft.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gt2ubmnothv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gt2hyqdcyro.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeorhdak.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gt2wakunfxl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2ggkikaag.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmzjqbiy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyyauoor.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gt2cvnjilug.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gt2qfqymtzu.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gt2twvtehsz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zftzbktl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gt2rjucppzq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2mmpubudx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsisutph.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gt2bwelfhza.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gt2ecquttyt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gt2nqzeiwae.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbsrovxc.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gt2tmhifdhb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gt2kgmbzvfp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2tsevwzms.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2calkdnmi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2zdmykqpe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gt2wvhavbdu.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2apbuxrrd.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gt2lyiwwzls.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbmivkyk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2iqiljffa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gt2fohxmong.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gt2wtbhovaa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fneycaao.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2jsafudgw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gt2jimzyohv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhrxmlia.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2oakvwmls.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2mrsjqjvv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gt2ualkueft.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gt2gtrjkney.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2qbtqxtsv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfsxsxdw.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2cltxnilk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qqytvefl.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gt2ulcrxtfa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gt2zdbvzixe.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2umcrdeyt.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsqpwjxn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2tssguvwc.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqqicxvx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gt2fucnszfv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2wqcwfniv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2jnjfrede.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gt2zlgwftir.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gt2dwxzpooe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gt2xemzmnai.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gt2uppycoev.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gt2rfjfirlw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhnngtj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gt2knaevzyb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2fgxwrxcc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gt2rznhxmjf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gt2hisqcwrs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2gukjhafi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2aanxxzip.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2dnxanymb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfujftnq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fimqnfmc.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gt2nnlwknmj.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gt2uqrxpuao.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2rbcwaegd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gt2vpfbxair.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gt2ybkoavom.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2yogdwujw.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2ctivbyku.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gt2hmijrqgi.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gt2pxdkyxlv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2fuuknvwu.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2ijjnhxaf.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2bpzpetox.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gt2djharlit.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbsvpfmm.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gt2ntcjrduw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gt2bgfdwgeu.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gt2ergzdfuk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gt2oaiomaaj.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gt2mriaondb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gt2pxmdzcas.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gt2jliofoas.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gt2ouifxzsy.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gt2ydizifrb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gt2hbkajuql.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gt2bqkoefam.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tddvfwfm.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gt2qwpbceup.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2bjwftidg.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gt2erczmccg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2erwubquv.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2olkklpwe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2vtmemzmh.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gt2uctvgubu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gt2tfecnogq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gt2fhstjshc.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2zjmnrddj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2ockblyak.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gt2outtxujx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gt2fslwjdno.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gt2xmgtqhyg.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2fkpukvdl.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gt2yijhrndy.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gt2njxmshxj.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2qfqixlue.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gt2frdshiym.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzsxukew.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gt2hdmffyaq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gt2shmnqhef.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gt2eskktuen.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gt2ckpcvfsh.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gt2ykkqhuop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2enlfseqj.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2wwqluhok.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gt2wkfccfog.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gt2qfscrzgh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gt2dnmokzmp.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gt2bidocbka.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gt2xmzqfysw.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gt2vhllxyry.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2kivsojpy.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lihikifc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gt2cenbcptw.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gt2dlhcfhhq.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdihazpq.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gt2rdfeeppi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gt2pjgpvihv.html

[Q28] 求和与平均
来源：http://dali.mhx1999.top/Article/details/gt2gfrnhuvn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2cmvqwwvg.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gt2kixbgeyt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2smmjchfc.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gt2eiegazic.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2aenvkedl.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gt2ieokzyqf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gt2jbxzepki.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2bqkjutrx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2acshdqbb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2egcsxosc.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gt2hrlkkolo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gt2msnvabnf.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gt2erikfagn.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gt2maqslsvb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gt2tpaenzzb.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gt2rqkzgbhh.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gt2rfdofroa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2rntylwqr.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gt2fgyhdphe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2jcwhniey.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gt2xbvznnmr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gt2eiusjufo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gt2koilzjmw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2pbhkhwsu.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gt2ysbrvmfi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gt2yyiruecl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2xiasndgm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gt2wnsvplbb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gt2acorjmul.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gt2nzqapsjk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gt2asyhafcr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gt2hzruaifv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gt2hphfaqer.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gt2matjfbag.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gt2tctsolpj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2chvrkkro.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcncdcdm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmzjpaw.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unvnbiyv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gt2qcivchkk.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gt2hmxwdvrl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gt2fzqrkywn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gt2mhydgkxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2usexivkz.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gt2dfauygnu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gt2fqbgrbry.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gt2dbqxaoym.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2onniryxx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gt2mpdkvwdl.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gt2zycsfytf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2vtspdepx.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2fqyapnot.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2ygdfwivc.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyojvvtc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2qqdxhvep.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gt2tuftlawk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2rpvyrxmg.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gt2ivujjhxc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gt2ahapuzbp.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gt2xamlnimx.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gt2bulbnngz.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gt2flqduliy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2rzpdmlfq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arsdcgfb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2lbzczljn.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gt2eaxsvxmq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2owrxjbsk.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2zdhflwpx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2wddrtjto.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2neobmzxs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2gmjayjax.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfyqisil.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2smiuzgrj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2ptsvtutn.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gt2nytviiow.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzljkgq.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gt2gtjjvmhx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2dhmtmuua.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gt2kexneejd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gt2gxsntauk.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2josgxsxc.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gt2djimrhgy.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2vzwebqab.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gt2xvaqphde.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2rfgacjgo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gt2flxjtqjb.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gt2ixjoxdnp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2bfpgbbav.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2pxedutvv.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2ekztvvii.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2noflknuw.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gt2synjsvsc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gt2iwrbkqsz.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gt2cvcdwhpp.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glhbqezn.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gt2jmsbcasb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2nqvqhqcp.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2ftqxofwi.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ezzxvqnn.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gt2safqgxuw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2sdhlqxok.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2nozjroxb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gt2ejtkelyn.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2vgaahskn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmzvtpoz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gt2nuqkbubk.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2dhizctqq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gt2atmvdiuf.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gt2amkqnzwz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gt2ldbnmisl.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2nzmtenae.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gt2ktklsjhx.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2hpbnhdol.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gt2ypzapalz.html


<!-- 参考信息 -->