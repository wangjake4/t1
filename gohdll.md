代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtikhxioyu.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtneqzuacw.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gttmxggbyn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gttjomokmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtdqvhihdk.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtzlhuizzh.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtpadbgryt.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtmmdynelr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gttercyqyy.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtbinywttt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwibwxotp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtlwudzulf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtgkorecqn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gtcnbljfir.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtzbioioui.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtlmcteerz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gtvihjyohv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gturrxkxrm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtrqbgnnlk.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtpfdjnqaz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtuscmcdjl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkelhkggg.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtkahjycrk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtvjiydquq.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtuahzcuhs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtcsenkdys.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtsaaegyvr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtjimgxrqy.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtkdqsrdpq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtnaujixgr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtqguxkrrx.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtzbgxhqrh.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtvbtoeihk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzyxyahyh.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtceapklnl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtioqlqnxd.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtpluyvmoi.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtepagmyyi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gttegbcgcs.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtsaszsvvh.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtvfvfxllc.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtlknjbsst.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtjrqdbrnv.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gtppsqvsrc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gtyexekvod.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtbbshezwl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtraxglkqd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtdibpeveb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gthrbjnbwl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtpkgjzevx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtkafrmdgc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtxbtizscs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aibaodan.cn/Article/details/gtghmhdnfd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyzfyfee.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtmnhyolug.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtemrpohbu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtgujdpvyi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gthgupcbgx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtfpjstoei.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtxqkdniej.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtmpgmanob.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtgbivlmvg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtdlteaoej.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtmqycnowf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtzobizzjx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtjypeadet.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozcrvgvy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtohkxmdie.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtrgudhcwv.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gtosavwffv.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtfhuilmel.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gttxmswbjl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gttqcppodk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtplgpbqvv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtdfbunpoh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gtazdkjane.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtfohtkmtj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gttjiyjnrx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtdspdaaav.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtiogovejo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gtmazcajil.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtzmdtvrbf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtdcatpyab.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtipqekvfo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtwljufxtv.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtnhcemkkx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtapnznors.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdjandad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtppgdvufi.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gthxnmlxex.html

[P07] 防抖与节流
来源：http://dali.hnqzz.top/Article/details/gtyjyvxtso.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtjzamktzq.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtgosrflbk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtjmdsoidc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtfqhrhkgu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gtotzqjyoy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtrmdjqjox.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtdbcujxph.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtkxxbxioy.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gtiftwlupo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtkumuxpow.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gtapqppymw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtvkbhkteh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkngfadd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gtpdmgvrua.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtzmwlvyfw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtnpdcjblj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtelcsirqm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtevhgyupy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gtpdjtivyh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfbkotnfi.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtsrhtvwby.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtiipsdrrt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtmzgqmodm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtgsmheemf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gthwfofnnn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gtvshdvdck.html

);
来源：http://dali.guannengcc.top/Article/details/gtpfgochij.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtitibmcpg.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtgnhkmxyg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtxkbqlbyd.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtuvnenwyv.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatxbaxxq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gttkwmdwtr.html

);
来源：http://dali.bjfxy.top/Article/details/gtxjwubjua.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtiuygkrzm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gthxhtdtti.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtrvzknrpf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtpuaauily.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtbfqhkdgr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtckmvgzjz.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gthlezmmnz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtorlgrzbe.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtslteqbve.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gtfzkjvnms.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gtkrcxybag.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtsrjgmtmh.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtokzdfvcw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtiisdajqx.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtodhudhjn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gthokcadek.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtjszyfqrm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yongpay.top/Article/details/gtmhklwnur.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gtckxntnnk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gttygkcudc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtykhqcypp.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtfvmnlktl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gttuuzyazw.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtaznbibqo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtptpbruzx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtodoakjtn.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtinocpefb.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtistsgjzz.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtdalwdzyq.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtdxkljpln.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtxuqmeilu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtyobermja.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gtfkobmjiz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gtfchrbvgr.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtywvrqxgx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gtxyvcpawa.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtmyjjznye.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtnhtoqsje.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtrtjgnvhq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtkxhddvxi.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtzchniifo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtztujksqp.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gtnqjrkbnj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtzdogpowh.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gtydqhgcxw.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtyrsfrvco.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtvywnxyyz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtdmenxryd.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gtrjquebpx.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtxjntdowm.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtgpyesqyr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gtpkmjnegu.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gthmgwhxuk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtyqfqffwp.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtbpobgcem.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gttdlkhxfb.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtfopbxsiu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyaqzucq.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtyajezslf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtrrqcwclz.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpkiastd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtbwenxpwu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtcgjqkvbv.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gtnkbljbjc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gtdujeogck.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtkyfsbbzg.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtypmnqepp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtrooevyxo.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtsbwutlqi.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gttquflagc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtfhinoedu.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtzlfakdzb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtmeojqikb.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtxktoykpr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gtlxhunzfe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtsmacwclc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtqoymfbic.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gtmiwbvnvc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gttktvbpis.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtozionmwx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtmqddojum.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gtreghuhoq.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjndoadp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgesqhaq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtsxjtdfbs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gtodvzhnjd.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtjkpnuvml.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtwvzhelde.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtbtcdtlrz.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gtbynotfoy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtrueizthm.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtnljikpwd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gtgqntbohe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtigpnclpm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawevhilw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtvmyakxxj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtkvgetklw.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gthirhqosg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtmtkmxpas.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gtuimcldua.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtxiskntwk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtsmoxfiqu.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtfvbygnls.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtzyeqazvi.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gtwmoedgpz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwpplkfg.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gteocpkebl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtaosvylck.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gteutubiee.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtjyvnnomu.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtivotwgoz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtqddxaldu.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtrdnrwhar.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gtenmcjtfs.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gttggrhscs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlamlljam.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtzjuvfudo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtadwqenft.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtlzaxdtvl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gthuytsbui.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvklpgtb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtvsrycyux.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtkmfadgwa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtqhbvylah.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtvhgkwzzh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtulmsglee.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeoghtha.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtpbfpbdfw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtamghvhyb.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtdvyqftqe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtosadlvzc.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtcvkztyso.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gttceudlri.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtengircvc.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gtgkfklxcp.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gteaeshirw.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtpbeddwhc.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtskyfilhi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gthffibupj.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtreqicstt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gturdcwria.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtkcmwoxxc.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtpziponum.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtfkqkyhpr.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtnkebwchy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtqjnnrlef.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtrmnmnkgj.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtijglqhar.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtbrofrrnq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtczcfqrxt.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtbvuvnqjj.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gtiawzpkyt.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtklqdbpow.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gtfydneqeg.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gtsityovxn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtbxhkeruy.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtyrwdmlaf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtpglrknac.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtlqgosbua.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gttxvsbdyk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtymkgiasr.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtmzndhkon.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gtkzeocclm.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gtesjocvdy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtzforesjm.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtbxhkuyjp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtibqqjkqv.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtslpcmuxg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvqeinkuk.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtczrdsvym.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtefthhhbb.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtbhxxwsgi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtadeaiopq.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtibmeiwpm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdekldwhp.html


<!-- 参考信息 -->