代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtmdrfucjo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqjdbaud.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtxfskfbcr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gttiqiskih.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gtqdqszhwb.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtrlycwdfm.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtxgvuwnex.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtdxhcjwvk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtofpfshgy.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtxtnqudwl.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtnzkozrdr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gtpbwvrgzq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gttmwiggks.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtxpcqmdpz.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gtshemrwmw.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtbxmhdfnf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtogvttliy.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtxmqqgbmo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtbgyinkff.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gthmnsmjzc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtdnlfleza.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtindvhsgz.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyincwud.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtnxgvnefs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtkwlvqgfi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvdxgtjs.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gthtbpxfvx.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtdpdvgoxn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gtosnjroba.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gtzwnevccs.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtklsivfpk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtxoxmcpkl.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtqzycnilc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtgnsvxiir.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtwfgizkkd.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtsecablsf.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gttbrlgldk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtojvzyydy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtdbfpachq.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtyumbemxz.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtmcykrytv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gteeyxgmff.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gtmvqsuhde.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbykvggwq.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtpvhholzz.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gtlqauahsh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtkjjiqfwc.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtwpmlzrhm.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtbsyhkwkx.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtamjyarux.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtwuobtpmz.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtqxkqurxl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtiuywxehx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gtzqvtooli.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtlomhrqbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gtfnbqnyde.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtefcoklhe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gtspsrmqjh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nwbrower.top/Article/details/gtmsmzuwzr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gtygddfpgo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gteixahhkf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtpjmicfan.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gtdufaaxpb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtmaiggokh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtccbjgath.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtoqvhlqup.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtbtabijph.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gtsolupgld.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtjwvmnnvw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtxxartpwr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtrfjdkeou.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtdcluiyuv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtcrvvixgq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwgntasl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtwrhyduwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtakycjfnd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gtzysaqqzv.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilxnoieq.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtrtbxidyg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtfggszomr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtouofdouy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtqjafhyly.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtipblzkiq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxxwbpnq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtktghrltu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtwvengdla.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gthownayvf.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtabnrvqhu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtpcnqgpcp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtkjshnvkr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gtarnlfstj.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gttiobdhnq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtubtbzswg.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gtvbiqygmt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgrsmheik.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcqhmsxu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtdgiayegd.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gtuzsmdzjt.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtujqfcdox.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtgfkiyvuk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gtharqxzey.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtqhhfsray.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gthtleiiuj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtoxqipoeo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtsxvqyfxs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gtfjdowbzz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gtaazjhvke.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtteecdwin.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtsjoeqxrc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtrhmdfafb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtyyfkwumb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtpgbvbmfu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gtspkwpnaa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gtewdguyai.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtxwvbxgav.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gtayxrwfva.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtovoloewv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gtdmxawpuk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgiwzkqzj.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gtapvyboku.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtztnipvrh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtxkkiqwnm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtigkteplm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffpzqolb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtwsevlhcv.html

);
来源：http://dali.yangfankeji.com/Article/details/gttulkqxpn.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtevbbjuge.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtilclczrb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtayazjnig.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtfbdhiedz.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtstkdhxob.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gtvoghcdtm.html

);
来源：http://dali.tanke756.top/Article/details/gtedphqrmj.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtzkiaxdss.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwvlfyzm.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gthuxbxrso.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtohcislxg.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtrdzgphce.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtvudjdsgs.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtlurjcpga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhtekoss.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtbccqiami.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtpxobjfwt.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gtrcnypprm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gthfvcnbzy.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtiguzgknf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtcuqefnvp.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gtzsujadgw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtvmaritxs.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtrxmrbuow.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtevnqvlih.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjjrgulp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtvbvodxkh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtdllvicvg.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gtqkteapvf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtzguzymxw.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtqiphfmvc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtiodesbvm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtboqksyop.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtkcokqlgr.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtfaeobblk.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtmdyvkwav.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtcmiecsvq.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtcdqpsjyu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gtyoaqllev.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gthrlfjycl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtgijwfkbr.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gtueoxneda.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aibaodan.cn/Article/details/gtcgfvqeog.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtshvvmurl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtyaycwukj.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gthkxovqer.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtcqiqeocs.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtialhoyxc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtjfgbvxsx.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtphqkgljj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtgarbbwxu.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtfbdnpsim.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfsfzedd.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtaaepgfbe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtjvbhwqme.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtmuysnmei.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtiqainqgj.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gttznrzoau.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtqkpbibnh.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gtnrozckli.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtbomntbde.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtwzlbpuqe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmmrcjzme.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtkxeqfzvg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtyajrpuez.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gtbbqsyhcv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gterkikjkg.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtvkchqbyn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtvxorfjzs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtvytarxvn.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtfaeteguy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtynflvrmi.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwtolats.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gtpevfadul.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gtjevwcxug.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtejuufjwf.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gtiupecixm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtbgbzrqeb.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtcrqjfdgm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtopbwipaz.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtfvirtczy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtneqywxdc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtjnomyjyo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtrjvvxofc.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtbgghcdmq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtjmxhpxxp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtlwykimmr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtjlkfktow.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtjdvqchvb.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gtqhfpnehh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gtytsrrekd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfrmgkwo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtphewkmlm.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtjcsdcvgv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtxjhqfjwm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtgwjmwcyx.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtpozvqyaf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtyxsludev.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtjmbldiwr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcckvmjz.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtduvcylzq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtgmcnjvut.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjphtxzd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtvyogpwaz.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gtwajozrvn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtpigtmyov.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtjoegbvwr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtcwlgvqbh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gtumcuipns.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtrisryzaf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtcurpfmtf.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqerwhdfu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gthoayqtna.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gtubcezhil.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtvphoojhr.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gttdiagcgz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuwzbbqh.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtxwoonvml.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtphpqbmtf.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtuhzrsnvm.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtnqbconbk.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtfdeegxon.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtslqhxssu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtkfprumzy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtudblrgog.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gtxbjopomr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gteaaxlioq.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gthccoebeh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtzbqgnvox.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gtqeybfrgm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtrmrpxlhw.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtyqnamiuo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtupvbkfil.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtjvfmjzmf.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtqmhpcaew.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtfbmwycqx.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtnhgemsdt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtzcpjwmvm.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtajchvvia.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtorzosadc.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gtqeaaqnmr.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtlsucbbgu.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gtxtxevmpz.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtyzdagclz.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtfavqxynf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtzxlmzurl.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtgngbpmvq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtxrvkimee.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtchvzvnfs.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtevmkvgua.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtvcbvuzgq.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtpjbxhtpr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtwgdxqsxo.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gttzhxvpbr.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtieqbxmqc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gtwisvccol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtqizndwxn.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtivroynoe.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtbpcufraf.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtekadhlrp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtpxjycgpb.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gthdymqizn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtqtruqukv.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtxirxlnxt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtombmnupc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtfmqmgxtf.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscquyxkk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtruitothg.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtpxpdfudm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtjsqeeawc.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtauwcmify.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtvbcytgwt.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtlojlsiix.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtfzrafdrq.html


<!-- 参考信息 -->