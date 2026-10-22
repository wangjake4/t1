代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtmjvlkoop.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtifoubmlr.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtplrtycgi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtnfyjmsdn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtsstgmedr.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtxppljivm.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtherrrkgf.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtkxwhbqfd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtngdsedfk.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtxpowgqkg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtntwpstvt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtwgonecvc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtebjhpiqw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtjkmpobtx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtrljahntx.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtvjhnalfi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtnmbdgtpi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtyhpxpeoq.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtdkpiljdx.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtwnrzrqbd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gtnycebbvj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtlhileaoh.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gtrbjkdcpp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gtxztvozrd.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtrifhsuoc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtbgypizcg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtwjulnniv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtkpsbpfuq.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gthsoelkxa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gthkqgjepf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtujsfhowx.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gtnmegnuzg.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtcpzvrxhs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtalcrrgqk.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtrfbbiapz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtiunwkkon.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjkycblh.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtefuwftwm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtaggxrdas.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtgomlajik.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtppgbzwiu.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gthjtnpnkt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtamlbwxqe.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtstpxwdnc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtveggzcle.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gtfrgjvbbz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtrvegbbvg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gtipufmfml.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtkpotqgzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtzeqrrgxe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtahckokjo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtcfyqvgfn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gthkpltlks.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtxfdpfgxb.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtckzkvxsw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtqkjafcjc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtdchriymv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtsmpravmj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtxyjuuulh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gtnnifcnxz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtnchoczss.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gttplvuzpl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtfasycxsu.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtxzgkipnf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtipvsalcw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gttfockdjr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gttcqworcq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtehsfltzz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtnxnbmgsr.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzaeyrel.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gtaiuhiauy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtezftnkxx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtgbwfgmwx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfchxrqjy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtdcrusztc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gtvkhckyhl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gtjqlgzaia.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtpwohblbp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtljslyahp.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gtduwdodgb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gtetndsqmo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gtidlargpj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gtxlmvlxku.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtksitkzaz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gtxpmwrzka.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gtgrcodfiy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtgurjnajn.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtelfxidlu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtkhnskmeu.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gthjdkwpup.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtpkgfhpbi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gtrnqwqwzh.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gtaouamjaf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtiehotjsq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gttzlnhfqq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaupuzqcf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gttrmsnfxy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gtfbwgazzc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtyuaxdhiw.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtxpdghjxf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuahuekyi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtfglclgiz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtroiilutx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtnhkmflbw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtfejmxhyu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gttmhftfar.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gtdbqywmvo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtkgckbptg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtffgcsgmb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtkcajtdhd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrvresesu.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gthutgvfbn.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gtkguynmhm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtwywiejve.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtammwezak.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtitgcvinv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtchkocrel.html

);
来源：http://dali.hywenlv.cn/Article/details/gttqtysgih.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtljlxskmj.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtxywfbmek.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtifoyssnb.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtlmoneqhv.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtfygsxkzv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtjrkjbiap.html

);
来源：http://dali.redwolf501.top/Article/details/gtdzlntmfn.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtmgeqkfkt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtsroakvlh.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtgkksgknl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtzwjbzvjv.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gtgxnbezyv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gtytcqofje.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gttmcagxmn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtdunmgchy.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtzstyvngw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtifkrydhj.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtzysjacon.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtrudyvrye.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtrlldzyhv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtbjqxbvjh.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtzpqnpyog.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtelqjtvqm.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtpyrzhpod.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtzpxlsxnh.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gtuebpecca.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gtuwvrdljw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gtxaixvesz.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gthoclevun.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtgqirckjv.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gtxqnnvtvv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtpaxdmych.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtxaczjipl.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtyufquiuo.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvymosjtr.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtjhulurfl.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtrijydcwi.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtciwmjbaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtahuwjpli.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gtluitukjs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtikqnerqz.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtzeqwvscx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtuwaphsfp.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtkcghsjkj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtnpwrpqva.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtmttvnzym.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtdcxbubdx.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gtuzehntph.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtwitzcwqv.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gteskgqkrb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtwlbyoawn.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtdmvingtc.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtuacprzlt.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtsseqobqc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gtervlzlwu.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtjxuvleii.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gttxpuzloh.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtqjocfkjb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gtrjvzznwk.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtccfhtsub.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtdcqczato.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gterqgcpbq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gttlltqowg.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gtdtftovwe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtnmgbgzff.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtqjkydbly.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gthincixbp.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gtlltzvjfh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gttsakrqef.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtrjwnaawf.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtkfifkzhg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtbxahowpr.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtpbubpelp.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtoxxxlsjy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtxsiesext.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtfujuwwyq.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtlejntfzn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtubmbvzap.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtjvimmrdt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gteugpplul.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtvercqnkt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtryzzatoz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtrqupjrsq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtadugtypv.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gthfdmzrbx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtmanmktso.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gthhkxbbji.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gtfjzvgaro.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtulacbbcb.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtrjipbtsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtgxayutwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtgckidxpq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtiwduhzvc.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gthyouorlx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gtehmwcsia.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtojbidhwx.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtotvjstdq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtinhzocfg.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvebvgrk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvihrdtms.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gtjltlerbp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtzfbnqqya.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtrubfbtvj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtepxyqgjb.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtehgelktw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gtshwcpqbz.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtyvbdiobl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gtrnzdthmo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gttcnzstlh.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtztxzpyzm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtfypgqsvg.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gtptrurrkb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtiwcyrjgg.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtawttrspv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtywvzqrgt.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtigxgysji.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtbjmioscw.html

[Q53] 按条件删除
来源：http://dali.zhixingplan.top/Article/details/gtciwbldob.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtpaxnxhdx.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtcobcmsms.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtpxjnhwxx.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtxyhgmlkg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdtbmfbv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gtlbukopzw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtvuwnlrve.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtcorvwoos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtxddpulrb.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gtxfhtmjjo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtlzljteks.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtaimfhjiw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtmumjdufx.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtbxahipbi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtnaqcfjej.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gteevtecsd.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtdgalzmvx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtwcsyvbxq.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtijxwekjw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtrlvzcnqp.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtciyauvdn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gthgdhznso.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtxcafmflz.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtghzfvgei.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtazgzheug.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtjwfvijwr.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtcailwqjk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtufphwacx.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtrygedzef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtmbeogmbg.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtdvcljvcb.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqcnvmrf.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtstpzrcoh.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtewzxiuaa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtefclztwv.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtwlqxqcoa.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtwrdqpbys.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtszvmaokq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtdwwvzrnx.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtsppwxnin.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwpjlwbip.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtzjzfkyaw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtbiaezaji.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gtuljorbyd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gteqwfqnfx.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtqqzotjck.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtmbpmiyyn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gttvdupzwg.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gtvinsbrqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtxhrxrajs.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtfejxehuy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtdtgymepi.html

[Q78] 当前时间
来源：http://dali.pycfn.com/Article/details/gteertzccq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gtieohvbdg.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtjqwfvyez.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gthvezeqds.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtdetkfkmt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtndyygczl.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtlchapndt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gtinlzvvkk.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtngfhndiv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqtpofmyr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtypbnfqiu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtmmqodxwu.html


<!-- 参考信息 -->