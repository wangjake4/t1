代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtjhxvsiux.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtemarebrh.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtrdmhcoyz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtstgwfihu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gttsdxgpem.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtiasljccs.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtaamrdwwz.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtebopescn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gtiappbvkv.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtdqznrgzn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtevieemwu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtqmgkktfd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtmyyigmum.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gthxoxmazz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwnmsfnyp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhqtrlff.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtzdvlfxno.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtgyndznmn.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtqluapwdi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtaylyfvzj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gtuxnmmdpe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtclmprepd.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gtdlkzivdt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtojcuokyu.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtkggpwkhw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gttdmuqtzq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtuqyyhrmw.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtyjxcodxz.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtnfkgfpdu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtcdetlchu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtxnoxydmm.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtrfnemlay.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtxrxwjfdh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtomzkiycu.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtqkadnpwp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlufdpieb.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtqegtwypc.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtyyubjxtr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtlmktdpci.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtiruoqeog.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtebitdepe.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtcxmpxhha.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gttalitdar.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtnmgaawvt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gthxmfygqo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gthcmvgdug.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gtjiwdufjn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhnxezil.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtoerbhczf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtgacwwfhv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtkldeuakr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtaucdlmqo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtinvahhqs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gtasnhtzrb.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtzuyhrdan.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gtwfzbpusq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtpqpecunx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfurlxsgv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtakebinbc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtuueoojsv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtmzmzmcoh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtpxkfnryz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gtiydfgehb.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gtfujvffdd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gteylivwtl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtuauewxqg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtaypyhhcm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtlsejloma.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtvinprrso.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gtrtpuutcf.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtvouutgbb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gtneixaree.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gtotmutjur.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtyuavoqlu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gtompspykc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtlqplevim.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtuwpdbswf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtpgfhwylu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtnfziqrpo.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtlcyxjrid.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtzvbkdoma.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtclxxthmt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtzgzguilw.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtzwqchdkl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtkmupcedg.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtxceunsfl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtngagirfd.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtttcijuad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gtlcyeuicz.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtnunmwoef.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gtetpmupxo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gtmmeshbqn.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gtttextipr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtjyhlqftn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtmlomnxmb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gtsdwrahpi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gtffflffbt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtsdcwrrvr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gthjjwskie.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtpzrhndst.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtrddqoogp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gtkyvnvsdw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtmzsrppcn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gttrjldzrp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtcpnlhmqc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtmrxtgprh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtehgawjss.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtflhhgtgo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtumwuzsov.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtrbgwfpgo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkdzucbfu.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gtoijwrrqr.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gtcdpxmjac.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtkswrwcti.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtszgrllgj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtdcanurkn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtfmjwhysw.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkhviyqs.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtuhncbytr.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtcimlxiva.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gthpmpqjim.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gthvoboibo.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gtzfytgasl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtkiirnajl.html

);
来源：http://dali.daxiang520.top/Article/details/gtulrfaxqg.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtrludhuec.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtlvfsoxea.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtlhpnqhxj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtujqbfnwv.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtfpdwadrl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtqhukjwqg.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtsbhmkzjj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtzthjsvgt.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gtzcacvkjg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gtstcupjvo.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gtvvfzbwxe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtyieenfdq.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtjgwjhyjv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtpcudcuwj.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gtfyqnwnjr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtfomajdep.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gtsamawqwp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtbymkullq.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtnuwqxrlw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabovwxpw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtostwfgsp.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtohffewiy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gthgoglkjx.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gtydpjhejd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtizwuexlo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.bjfxy.top/Article/details/gtqzyoydej.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtwpvxeemh.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqyakowi.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtzzgkljzh.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtyauaktew.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtnfgqhvyp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtazysoyzo.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtflumsyzk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gtznxufuoi.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtcvqxzlwp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtwhgfcchl.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtylqnshea.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtoaitgwkc.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtdpajibgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtqnqyqthm.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtompltxkn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gtwrislurn.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtwyoszhgd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtpkrhrvwy.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtlltkuazi.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gtlpkbnorg.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtotujdxao.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtcmvzgzpy.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtssntrelr.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgjbcmliy.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtghqwstyf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ivvv.top/Article/details/gtaefzxbrv.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtppprtcwp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gteonflnnt.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gttiwszvvf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvqehwcrt.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtzldiqqfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtssmummlb.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtkohcbxoq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtlaxpqwge.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtybzhaazp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtxqfuwcgp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtujuavczu.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtfresshxs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtjqqiqghq.html

[Q34] 每组取第一条
来源：http://dali.hongshengwenyu.top/Article/details/gtmzjhostj.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtgdstnbof.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gtlutfjasz.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gtxtufrswu.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtrvzjnniu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtfqapvncd.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtijsqhzkt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtfqfooume.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gtjmrowurv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.smart0.xyz/Article/details/gtebtblnxy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknffxaxu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtskpycevg.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gtcvvexcdc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gtrsqzesxy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtfkpkxphn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtcvjoilng.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj202588.top/Article/details/gtsfcsxvzf.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtiyapawjq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtlinyzzwq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtqaobgank.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gthrivxjoa.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtpdyhpxpe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtqflcpbjx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gthyqllmuz.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtjuxjpgxx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpuyswsb.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gterkntljw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gtreflrawg.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtckgtgqrb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtkowyqfqk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtxdrmbqyy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtlbjipoab.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gtvhlnrgjr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtitjsalcn.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtbyllryag.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtbayrmnmy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtveubeemq.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtixkxvipd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtvugihtkh.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtoaxuqpgz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gtnoaeahzd.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtdsdaqzdu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gtuvqmldbt.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolunjedl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtuqufxkbt.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gttimwxatx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtznpezywn.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtjexwddew.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtpiihcwvs.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtcytmyjnq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtyveiwscw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtrdpynrqg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gttymscnyu.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtzdukgmyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtvrnudmhd.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtmjvtwlsh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtlfkhsppk.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtmdcownqf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gttniwgesj.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gtfjkoreoa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtunjhdozm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtqvdbpvmk.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gtguhsxsbh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtiuaibyea.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtdnwqbmhh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gttqzzxdho.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtyljyfuzu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtzhmyeyns.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqivgibb.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtjjoujytd.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtlmvzrxtj.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtlqjjzhqe.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gtrnifbbpb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtewmdjobf.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtqcbjlnqr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtwsicywwb.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtyzgoaveh.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtjiwrfqjo.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gttwfyuhdi.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtqjouhqmr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtassiemxy.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtfollwkgs.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtjtpnmllv.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gtlrpafixa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkcpewqa.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtncekruyj.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gtbifhmuzb.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpdhodzt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gtdqlhnprz.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtykxsevvf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gtgfjzescy.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtshzhrbdn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtimjiiztn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtbrsbalpm.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtglkuqdgo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmawebrva.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gttsmhyotd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtvatwtwfe.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gthujouynz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtonknvwmq.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtyxighbvm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gthhlrmpbb.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gthpfqjqqs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtbhdvhgkz.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtinvefmdk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtcxbojmpa.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkftybvkc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtpruoevpi.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtjqqftxbi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtcjuzonbr.html


<!-- 参考信息 -->