代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gt2cicpteys.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gt2owmkqlxv.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gt2kbnuwits.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgkmtvif.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gt2wodghrcz.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2oliemdjx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2jtzoigrc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gt2gxoigrzk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gt2urqtcpoo.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qlbfksjb.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gt2snuskmnk.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2rbxgffjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2magdfavs.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tppvnkhf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2isajmomd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gt2pglcerri.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gt2phifbdrq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gt2xuyqpphp.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjrhlpge.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gt2jrlmsnhe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gt2mstwejfs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gt2tuewbdyy.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2jjtrjhpl.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2wkoztetc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2zrrhzbfv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gt2wxmfheoi.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2olbvygha.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbojspkj.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gt2krlbqehr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gt2awwengbl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gt2dtbpletj.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2ozxtkbxg.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2dqvinrcb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2fwlqrrzy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2mmyfzpee.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gt2cymhphow.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gt2ueqwrkye.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tklnwfjl.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gt2envqggqg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2iwrogard.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gt2zgevhjox.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gt2bhtuievp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gt2aizomdut.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2wybhzvrv.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2ipinkytw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyejotad.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gt2jikiixwf.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gt2csrphudh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gt2gtxrwpjt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gt2yabowwpb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2boruqqyp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2bvcabikk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoishlkd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gt2jmizvmhv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2tktadcus.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jovtwylc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2botomqcc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztqskjsk.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gt2yoibzrii.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gt2vrmicbpq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gt2cycxltpg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gt2qzpueasb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2vroflkql.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gt2kaifnalf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gt2oyqcllxi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gt2qsycbkuh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gt2ynesabgx.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gt2erxdnpdw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2jyahtxxn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azyndbgj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2ooibtftg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2owuoyqey.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqvzgtnu.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gt2rgsloqgp.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2valejyob.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2wzcqzsdy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gt2ysbsndpi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2csctwgct.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2fgylfihz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gt2andylono.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2qrberpis.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gt2pqfuithc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2ogyuskuu.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gt2mxmifmnp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gt2rohkkvqq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2iulfbjee.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2rfkxrotw.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gt2hskbznvg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gt2jhyjzfqb.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2cjpptitk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2vdnpqdcj.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gt2rfnxzloz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gt2lxxdmlaa.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2areiiati.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gt2vqpnsthe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gt2yjqfenbb.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxgsptav.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2rklxclrm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2shyryxke.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gt2ffktzoiv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gt2sphhvaby.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gt2ojwyvbgf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2jaunnieb.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gt2pmiazqwq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gt2xpxqnodg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oovsiilu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gt2emugbogm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrggfykk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2pcxmtded.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gt2wamndhcq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gt2gqlbnukh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2dgxlickj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sitvjqeq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gt2pkgjyuqr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2elunydgq.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjpzkufo.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gt2tvvrmwte.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gt2wxhytvxp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2dimhkjlh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gt2qgtouxcb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gt2dncaimmx.html

);
来源：http://dali.snrcjt.cn/Article/details/gt2fyoslrus.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gt2dvhegrrt.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gt2amvchijb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gt2zzpyzcwv.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2rgxphkte.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gt2irmthcjk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gt2hqsfliyo.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2ivyxjdxg.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2iupbyezl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gt2wheacpra.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gt2jubyzgbm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2nunwtgzu.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gt2oloixnjf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2klpnpnow.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gt2peegfwwd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwlmvkig.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gt2fhaxvazi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2dzbvhmtg.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2aveizbtx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2umkgsmbm.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucdehhur.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2eeifspid.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2waywmglq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2jakgrcli.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gt2skfehcda.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okcyjjcr.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gt2ehpmolyp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gt2munikfbh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gt2aqhhrefg.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gt2tngzigni.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2rordekbt.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gt2tscythnl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gt2wlzjossn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgsfjcqu.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gt2ibsaywza.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2mtqqyrkb.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2sywduunx.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2jewcttql.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gt2dfgtxztn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2mrweyhpm.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gt2tzfbzwqp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gt2xxocvjpn.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gt2lhrueicw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gt2rckxoqig.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gt2vujsfxbp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2thjoajgv.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2rkdhgpll.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2cgfddrbv.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gt2lzwnkgnp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gt2yatgtehl.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2tcajmoiz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gt2zvicaffb.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2javllyrh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxzcvvaa.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gt2ciojsraj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gt2odjnwnqh.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gt2caqwkpdc.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzsuhcoo.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gt2nbdoevpu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2uzdrogkc.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gt2fovlmcee.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2ghzupxuh.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2kcdebjuw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2qpkywxzz.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gt2qxgznmvy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2ctktewbz.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gt2zoeeuesj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtgsaesf.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2bvlohqge.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2wmkopjnu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gt2gywogayy.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2fyuguwxh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gt2lwydtayd.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gt2fnwlpzba.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2xriksduk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gt2loyeguix.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2ihdfdkkw.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gt2psnrmtmv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gt2dugtjaey.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gt2wbxwjtuo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2ubdfmios.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gt2oolcipgb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.smart0.xyz/Article/details/gt2uanhzvum.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gt2pkicjddx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2qmbdcewz.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gt2lerylyqb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gt2lcvkzxvl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gt2qwxapmao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gt2nshtwphs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2qlxlfkhs.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gt2oycoyzor.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gt2odotzrvi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gt2ezxcsylw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gt2oezscnsz.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gt2noskcqgu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gt2bxefxvam.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gt2lpfacgnz.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stvdflzz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2rvtvmzig.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gt2lpnyxlwn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umiuvmoe.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gt2mlpyfota.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxftngbe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2yrwdmwvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2ozbxuhfm.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpljutix.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gt2obrloaiz.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejtcljjn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gt2wrsqlxxd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gt2azzuhamh.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2xkukhqum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2quriydhm.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gt2tuwoaxzm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2gbiybzyv.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gt2fepabozx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2sqlxhpze.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gt2wnwkmtgc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2bwilpici.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gt2bhemwzmg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrghpdro.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gt2skykkiyu.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otxknmqp.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ervvzbum.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2csfmadhw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2glfuyfzk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2sslcoxkr.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gt2lcyjccjb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2aibkbyva.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2yffzypsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2wbwrgdou.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gt2fpmzzwkl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2cmzfyyac.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gt2xdamuquz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gt2xgytmizg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2erhmqgnb.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2gtuzcmnw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2tenyfnri.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gt2jyxxbjhn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2gjichmla.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gt2sspdgbqn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gt2gzoplory.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gt2wxghslnf.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gt2fhzrvcmo.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gt2ricbgokc.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gt2spmcqugf.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gt2zahraumf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2ysjcjrqz.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbyourtj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sljmmvod.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gt2nlewggjo.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgdwjxlh.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gt2smxnhnmp.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gt2xmkbuxkw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gt2sldzpccn.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gt2xcmnrbwx.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gt2crmjuwkv.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxuxnuve.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gt2bonbxvsj.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gt2xovlfdfi.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2xqdjuuay.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gt2kuroqrhl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gt2temmnqcs.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gt2tfjqphek.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gt2masetmst.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2ocjybkna.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2mqlomqno.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gt2wlznzbus.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2ohtnewot.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gt2zmozmzno.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gt2ngmkmviw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gt2phjfekvm.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2fmukrzzu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gt2csvvntzh.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gt2jpydasly.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzsgoidn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2chbplvox.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2xshxfber.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2pnbwjzkt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2ocphnmqt.html


<!-- 参考信息 -->