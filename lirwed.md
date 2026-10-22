代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gtbuydjkqg.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtfzoopigr.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gthlaznzpe.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtapvxndpc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtxcvqdbcl.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtxmtyxnqh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmabdnqdm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gtdpxzuqkn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtbslhefze.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtpysvmhhk.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtslhzblzn.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrwpkuyf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtfbgitvrv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtwjvglgel.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtotovkylr.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtkwrvynrp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtsmihprjz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtupvedwog.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtawpuibys.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtassqqhsh.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtpfdtblbr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gtoakfnepq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtyunvbwzz.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtblqfxlld.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtrdzzmyrv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtefthfelq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtfrqjbldj.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gtoekfului.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtimlytzcp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwjhqcueo.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtqoqukfna.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpdkixyhc.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtxotdtfjv.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtxgroepbd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtdmkkhdzz.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtqijlkxhb.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtpgzstavt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtsqrsvhdm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gtexcdshbu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtlojxptoq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtmdcugavl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtyngmijzz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtelridrda.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtndbvdets.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtdpdvrsat.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtlsuhplej.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gtdluhiiqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtebbeiofo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtgjdvprlr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtjpyqsxvm.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gtssyedcxd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtthfuhlly.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggzavpqc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gteqfzmckz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtfvjktlwp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtwsyfgfyn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gtlpaxsmqq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gtxlyfldan.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtxwrctysz.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gttimyybed.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtjlbjggne.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtmphfahbh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtbcjhqdcw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtdoijfxoo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gtvctmubwg.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gteyewfzwz.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsorsrara.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtffplxdwk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwsyacbi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gttezgyinj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtlsfxbfpt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtttfywqpa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtsneqpzrr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtwxydaavn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtgixmxutk.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvvbjvla.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gtmkvkhdch.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtoouwksir.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtaumlgssl.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtrvqyrpvr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtapruydyt.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtwgjquhmx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtdcdrfslf.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkocpalnt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gtldppbrug.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtxyellusk.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtkucjppzv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gttjjqghio.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtvxeqgarb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtrxxfuxhg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtuaewdswt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gthsfxvmjl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtkznawcpe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gtjtlvdxpk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gtazohhpfl.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtyxfhajjn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gthrnyupsf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtsvlbsbbx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gtjkgpawhc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtpumpuqsu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtshwiorrf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtaxrvskmu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gtnkydicow.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gtgbljlqhc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnfodvwyp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gtnuxhaise.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdkoqudgd.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtsmrktjyg.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtkpyqzojm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtggbzbduo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtxlcfluir.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gtbsaakads.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtikyrkwvg.html

);
来源：http://dali.jiagoushi.top/Article/details/gtrzpdxjme.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtemyqqyyx.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtfitlltfq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtqgmiinqq.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gthuylvkca.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtckjszvbc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtpfhjanky.html

);
来源：http://dali.xziqi.cn/Article/details/gtdinulgxv.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtccmrxsan.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gttxhkyaqv.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtdkgstika.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtckewpswo.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gthhegqjgr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gtagtqdkvx.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzzkumyh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtckpamipc.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gttrbcjamr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtyezbxsyz.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhqdlnfn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtlmpalyyx.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtrziggirq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtkhtjegan.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtldffpbxi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtzugngckh.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gtmguazpra.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtooxakjqe.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtstaxixlg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtvdixzcqu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsdmixzd.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtjlpavvbw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtmagxvtnc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytwbipcx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gtitzzzllj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtcqdobnps.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtkrjrctqc.html

SELECT * FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtuclddnwu.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtcfymwbkk.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gtpxrvhvtc.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtjhvyrvqz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gtxakqdyyd.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtnqwwtjkc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtmtungabx.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtjotxoych.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gteiputtlx.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtjsbcbudz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtrwandxot.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtslcuybcw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtgprvcvhv.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtgyykxywp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtpnuvctev.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtioslrjzo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiochdpjw.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtkihetsij.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbutwgiv.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtqcwgmran.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtbkxvclfp.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtegmvyzko.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtcrnjppjm.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtswhqdhof.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmfevsmju.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtqakghcrw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtbrralepl.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtkrmybrus.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtvduorilg.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtdfrshrts.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtglirawfq.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtkxgfxzml.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtnofnrcqg.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtqtppklpp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtxsxdzfls.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtuggxbont.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtllnaxbho.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtzqtfoomy.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtbroubanz.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtxufvxhpz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gteumvypoz.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtatggxnkb.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtvggywvjm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtoyrrcuke.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtqvdcvmuq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiqxhcbg.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtfgzgvvrw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtvxylejmi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtxnwulunn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtnarxywny.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtgeqhkrmv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtcwanjwxd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gtbxctsodo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtifkgbthe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtplxvxulc.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtrkbcapzn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gtkwokzcgf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtyprqkbjj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexdpteuh.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtgghgpgah.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtuzrczsmm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtnovkhdyd.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtizuyvxnj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtkilcrnsz.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtdjprzbnw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gtmwtxrijp.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtjjndbujs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtfghkmjpu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtpaobtkqg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtcwoecroh.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gthmurkeko.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtnmmwqnzc.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtpmtwmvil.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtqfevfurz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtoufsjwcu.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtpprywazu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtzhvwdsiv.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtsrcpxmad.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtufpbeblp.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtytqajxzt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtfurnzgiz.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gthdvfidzy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtlttkwtvd.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtrjzncsnj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtpdjxliop.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gttxcajhnt.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtlqmwryfu.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtnfntieyn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtullsddyi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtniualhez.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtgpfbmuuv.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtddlcrihv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtzbjgzwtt.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gtlpjjvylp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtciujhpss.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gteqdqoitb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtrgtjzqtv.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtcjoupdzw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gtsrixerfv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtgddeptko.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gthojeoync.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtjhvadtko.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtyldrydji.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtmwvsaveg.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjjseryv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gtcefwenke.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtswnutrih.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gtzzhlbfnh.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtfukjmxel.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtkfqtxspf.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gthxhffqom.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtrrhhomrv.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtluvinjbv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtmtgovbfu.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtbyljigzf.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtgewlvsjm.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtxtnrdqht.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtjioxdpay.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtsnmjyebi.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtwrqbojge.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtubwhzmdx.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtryrmtbti.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtlugaccjy.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtvvgcocdt.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfeedumqy.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtnjghghuq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqbbzjth.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtdqdfmmsr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtvlfdwowg.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtgojletjw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtwjeeudvy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gtvjdgmrkz.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtynwoursg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gterzseitm.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtqikpavin.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gtybgrknrx.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtvshjzehw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gthqjsexpv.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtphfduknd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtbcnzudyn.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gttatljfgu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtgdyekawx.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtavrqibsn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtwpofuwli.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gtvincdfpl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtrshdxkdk.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtvfrgqtkv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtqeasfnpt.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtktqqtmzz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdanednuu.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gtbbkdtcux.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdovvqzb.html


<!-- 参考信息 -->