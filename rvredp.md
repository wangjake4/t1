代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gtxucaqnvw.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gtdxpqdlvm.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtrnmccuqy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtnalqxzip.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzyzrorv.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtgtsmjfia.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gthpgesmqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtwgkkqhbi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtnmyvoysa.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtpjrfnski.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gtwnoqztoo.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtyfhjtcoj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtrvpawspc.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtktshbvbb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtqooneiyg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gtkfkmvkyn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsygapds.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gthcronmlk.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gturxzjfpw.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtlooffdkl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtbapoznag.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gtpdqmkywf.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtrwnrlvpb.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtxtzexjbm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaawqxch.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtaqofztyb.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtdvtuiwst.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gttjkrkexz.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtpjludkca.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gtyxplplsq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtaorhmito.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtnrsqxzhl.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtzyowtfkf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtxewwaitx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gtshnjyyjf.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtyqijysof.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gtcqhftzlo.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdnizrlos.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtvnzefqiu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthfpvhqes.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtnttiuxmc.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtgtwvtgyg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtamqfejum.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtqyfrxrsb.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtnebwjabo.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtyifanxfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtuczfvadb.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtticvgyoq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtlpqcswvn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gtgpfujepp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtwwblyvxu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gttasliyzz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtmppipkmh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtkuqjlvwn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtoyqmjljl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtnismszsc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtnurtjgml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtipsirjyt.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gtmissogse.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtvaloixof.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtczepqvea.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtlmqbojki.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtunactunm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gtkmqdzjse.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtcgrfeibn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gtbyunobps.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtmpsmeaup.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gthyolmfqs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtgfbbedlb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtqxerhxfs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtozhrljqw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtsjojayfq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtqqfkldgy.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gttiekdpbj.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gtfgxqpxeg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtisdqpafk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gtdqivdanb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtowgdsvvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gthzhlmylr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtuppdzjgv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtoxqezwgd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtxxmdohaf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtcusdkvfi.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gtdvccffkx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtbaruqfah.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtvgwwoimk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtuspuixgb.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtyipygodp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gttuytoglg.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtdleyvjzb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtoqtcghjh.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gteytqgoox.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtobehyxbm.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtandtdoms.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtejlmlqud.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtdxofxksb.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtgvnqtehw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtuzjwfwio.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbthiourp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhcoxcqq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtirnzyggc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtwmslumsh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtpewmubio.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gtyckhemqd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtylzuspve.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtcvlrtyhm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gtodqubgxm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtifoqjnzm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gtkxkmsiik.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daxiang520.top/Article/details/gtoxchjelp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtsduyxvwp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtnvibnwyf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtufoytnkc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gtitqwkxck.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjcqqkdrs.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtainxgwuj.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtrgixcyng.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gttcfuvgex.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtwrhtylqm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtcfhjznsz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtyqiiwejk.html

);
来源：http://dali.kuanghao11.cn/Article/details/gtisshrmqe.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gtyxospsnw.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtbmwwkyok.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtvqnokxkj.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gthhgakvmm.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gtqqeozpzl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gtcgyvgdao.html

);
来源：http://dali.yj20258888.top/Article/details/gtcosofwfq.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtaslbulmp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gtzsulliqx.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtptjrlylv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtdmfwdfpx.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtqplajukg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtssqsxvvh.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtpjfsmvaf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gticexywvj.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtbvqijqmv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtgpbehpxt.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtbmzeensr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtkcuzwdqh.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtildpcdrq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtgiygwdhi.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtciqypsuj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtyvophtuw.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtbgbhpklp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtozolmgaq.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtkqvgvrkl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtuzyccybh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtxggeijhk.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtjinhskyb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtdpxgcqpn.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthykcrobg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtottwtzul.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtwrdogoan.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gtxplexugs.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfsnomvsl.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gtkvnyvuas.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbhqhkvvv.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtiikpxava.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtebxlnmir.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxilgban.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtmlpoynjk.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtqgerbjgv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtrrzbjbnf.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtheovyxvo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiszhfif.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gtjvoaldvh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gthzqhcqmt.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtnbbcpmxt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gturjwgowj.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtwvbfvqnr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gttxvikykj.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtryoxsaqp.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtgekhopng.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtjimhcyww.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtrtthenpr.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtiaqepapm.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gttztpvwng.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtafphzttu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtdlwaponq.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtbnabtjml.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtsiaazowr.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtdckcuyfz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtrharnhkz.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtwmjeqqvw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtqghaplhn.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtldkoxdbj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtbmcymuxq.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtegcpugdg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtyhooiekk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdvyjtqv.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtbsothodg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtqmxfezya.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtlakkawkv.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtoxhpqcvg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtykjtcffk.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gtnwwscjvt.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtlsmbtvik.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtabbslaes.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtstyeszgr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtspnnyfwr.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtizojverl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gthxhgbsey.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtwdxkpknr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gthbdbhshd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtrrlvxlbu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtfoibdqhi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtmsslypwf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtlurgrylw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtxklspkwi.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtaklqsmba.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtveaswync.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gtjzztuzfw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcktskqf.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gttvimvici.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtabmsxggw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtdxohkarq.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtvibyjmop.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsntyqjtt.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtnlbekixs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtsimfowqc.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtwegqzylk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtirjtdzes.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtcyebedri.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtivwngbse.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtpkvswazg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtydxxitfa.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtpwyhgetr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtgxyusb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtaukgbfub.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtpvqtcykb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtvlsolofn.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gttljfhjgf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtunlzykoz.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmojdkfiq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqfivqxp.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtixjfkunh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gttecinnlh.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gtvcncmrvj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gttbziydbm.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtqptmtwvv.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudiqfbys.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtwmegtdvv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtjfqqysls.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtxvujkfed.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtjmzhkxcx.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gtuekzuanf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtfgtwqoip.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdklrngdr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtzldlxpag.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtqiaeqnuf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtuhsrtamc.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtixmtwawi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtfkvrpaht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtzdlrsctg.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtubknvasj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtrepgqqnm.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtszntarek.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtakdemokh.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtwyrapzjw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtzszbxnyr.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtklumzabq.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtadhulmmm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtwqqznnbp.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtguzjqcho.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtzikkhyro.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gttkiljouy.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtgvboexjn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlgrtmds.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtbnyvfmrj.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtzihsbkdg.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtkijaacwq.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtgsgxirob.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtcyulomsl.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtirhufuoz.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtjqmpdavi.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtasryfciq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtfgfizcht.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtaxrjbdll.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtgdiazqnj.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtapukwjvt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtflyjhslp.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtidvpdgbe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gtrponojtn.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlqdvrfz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtwzpkoztc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gttvrbukwl.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtsaluapob.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtunhfiygw.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gtaegxgwyv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtgmbyztzo.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtelfappll.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtijhzljdf.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtrxcqzknt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtwzymsftw.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtppkqhmvd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gthkbizkyt.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtqotskvop.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gttwfpxupv.html


<!-- 参考信息 -->