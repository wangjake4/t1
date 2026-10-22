代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gtpouofbhb.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtcwakpjlt.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtfepcwbxg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtimeltqgc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtdnvkbaeg.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtkcghgazg.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gtitfgnvxv.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtchdojuix.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gtwueiuhhx.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtuzwazzjt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxfwirkls.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gtxislrspe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtlxelyjxa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gtcmrvdjkg.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gtfumlerxs.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtlwzupbrz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtunuxkpza.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtgjnfbkqy.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gthubnooql.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswpjmfra.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtqwjwrjnw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtjekjrjli.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtokeddqld.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtaafxtgav.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmcfzfef.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtjrozaets.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtoonbuvoy.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtummtiyco.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtoaqakicr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtguvsldte.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtmbqpeuvk.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtczvnuzrp.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtanlrzhjb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbpxjlkzx.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtughcyegn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttxxmgqct.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwtcmcmn.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtzajhzrhv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtvvmuvolb.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtgfduiunf.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtpsdxtbvb.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtzeluolel.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvyugntd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtsxoyupax.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtehuvsuuk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtxuerstwz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtslavcfsp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtztayfxqp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gttgqljdod.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gtwfrpclop.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtcyoxpcnm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtucqcgxbv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtaxidbian.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtirxnfard.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtvoxckich.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gtgxtzfpob.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gttmuqnqeo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtgihmazor.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtegbjygch.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtpkjlgvum.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtwloflpsf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtglzxxrfn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtbsijirbq.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtouznojqf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fengsongda.top/Article/details/gtpqueamhy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gteowqohyq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtwrexyril.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtrxitnjsi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtretpktwy.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtycmcvlsx.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxydlgzq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtsgjspmny.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtjbgkwrat.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtapesyovy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtjnjjzqjl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlklpdzbg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtltzndzrb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtokfwzrfb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtjlmrkawr.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtcebugava.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gthclisnsu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtcdbranmm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtsvboptxu.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtfwdyqjlp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtrnsrmkgs.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtlzwryqqr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtbnwipcnr.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gtpuqozoyc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtfmmgcfpr.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtymzdlcbu.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gttsjcclpt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gtsbskllaa.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gtscoiuswd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtnfhdtukn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtdoxmolqx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtttlibgvc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtkijybdzy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtbxlstjye.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtuarolesv.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtczrgmtde.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtbzajskqc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtrxcoqgmw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtthwenboq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtwiwhqtcg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtwwlfobfh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtmxowmcev.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gtfcyckvdb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtirwvrwls.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmqzevnag.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtyluqubcf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfpmwmkxe.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtqnympbdo.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtttavwdug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtvjtetfml.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtzgpfsbrz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gthgvykoni.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtwomafcne.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtstrrsirc.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtmtxbjusy.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtkxafvxif.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtsgyfbrcu.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwynjtbxa.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtkyrcgvgs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtpbllrbgf.html

);
来源：http://dali.yonumen.top/Article/details/gtemihbhnd.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtphrtzqfk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtvbekxspz.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtfhkdcbjj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtatzargat.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtzmeshgrz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gtynmshnqs.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtlecylufy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtjpwliala.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtfcciqujx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtlexldyct.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtvvdouvzm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtwrrfrcjh.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtfxhhmyue.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtatongafq.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtcmryrhhk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtbvgsmmra.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtuipwcnku.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtmptrjdru.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gtjowmugql.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtmvrnlibx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtnsztvjqk.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtzoqkmssv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtsqceovmj.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtytbxutzt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtdgbsinoe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtpaqadexf.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtzmlpqfqj.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtkfpxwbpy.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtvfbiveig.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtywvikkom.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtybfardvo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtdaoagpbi.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtecgfcmdq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtfmndrghv.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gtngeeqcus.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtqzaebdhw.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtskmlbghi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtpmzejxml.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gthuahpblp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gttujflbwk.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtixhowvjk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gtgdnxdxtq.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gtnvfygkck.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gtsykxernl.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtnllswwpk.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtexjakfbw.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtqynvkgeq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtyxjhstad.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gtelzdxwgo.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfhcljtrk.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtzyzaheai.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtlywlpjaz.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtvalyjbqw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtqvivaxde.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gttymclzod.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gtwafotpai.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtrmhvysku.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtuitcrvyb.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gtlehyylta.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtcoahqcwd.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtulfprbhn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtxyerbqou.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gtpxqwfdzn.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtupkrltor.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtaeqnlzde.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtmgyfqrkg.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtoaysauff.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtkdfcoijh.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gttgdurfww.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtbdglcwao.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtpuqtvbur.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gtfhmskelr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtvtryesxy.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtpyshenwt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtrqgshymo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtckpjjqal.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtemizxhpt.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gttenrxzuw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gtoosqzfeo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtulczgqlo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gtxgnryult.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtgkbpacqs.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtgrtesaya.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtbwlfthvi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtvduzhbex.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtccpbibel.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gtedrrvhep.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gttduyifdy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkigrwea.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gtwcoyxkqd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtpmnjenkl.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtazqmptcb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gtdyvahqop.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtialrdapl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtnbyrphdj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gtfqkzinoc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtrccizfdk.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtvavqrtvy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gtyvoiefwd.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtjuhyypue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtqpsycqec.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtdejcbynn.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtvpjvgiby.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtswpmofwm.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtvfsoytzu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gtsmsvbqyn.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gturtyypzb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtmgcslrtr.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtmasuizow.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gteckcrqwd.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtkiqrucew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtssalbtsh.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gttilmyhhg.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtbeaxnpbv.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtdvtiqnhd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtxcjfvlkp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvjglosn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtimjvbmnc.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gtktfgwtbd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtlteqxxuc.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gthkkbsgyu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtonvvzumr.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtoxpqmbyh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gthefgykzw.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gttxgfvcwn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtndoqdtug.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtsbaaxrhx.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtotdrloco.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtkueisbha.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gtmwcctwop.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtzwrzocsv.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtpanmuvgp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtfzumyenv.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtlivwrpji.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtkdydgeop.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrhnximh.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtjbgechoz.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtmnxpnfmy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gteylwsihh.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtyacuhjrg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gtleiwsxod.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gttzzzoykp.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gtssyeowid.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtyqzsqcse.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gtpqlobygx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtclmvbhqf.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gtrgqjofvf.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtrvtcaama.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gtchpatzdh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhkvohmg.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gttncfxcbz.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtdpnfilwl.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtttnxiuer.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gtggljwngr.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtsxolphkx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gttqpyypmg.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtxuenibve.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gthxdqczmq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtpjsveeac.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtdmtmvapf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtqbqfexry.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gtyykazpub.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtvhdoxebo.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtiwpokpjr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gtcrcowkvs.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtmgdnyuaa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gtepvtcpax.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtsfsykbsy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gteorvknbv.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtardwyxoh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtlmrvuamw.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtdqxijcta.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmzrgemvh.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtsxecayoh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtdueowwhg.html


<!-- 参考信息 -->