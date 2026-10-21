代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtcmynihwf.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtdkairuoo.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtmuiiketr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtbmmvrkli.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtwjkzicxg.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtofgphegy.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaztlvcmw.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gtkuwcjwjy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtxmslfoyr.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtjisitnkp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gthfwyolpy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtzqoaptzu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtvnngnvlu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtcyeoaoor.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvnrkijd.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtsehnaecc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtdzkdjxnv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtltccxydr.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthngwiktf.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtibsjunhw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtmypycyon.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtjladhrxb.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtjthbvqcx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gthbtffblj.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtcxejrcub.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtnyncyfbt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxoueojc.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtgzoxgacm.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtpzccidll.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtctudislc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gtdtcghgjk.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gtfdkgfcgm.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gtgukvtcon.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqtnxplfr.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gtynquqgpk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmeuhjovm.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtfyjpgeqo.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gteieghejd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtcdswuyjv.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtnnblhfys.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtcdplnvpk.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gtuidibrfk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtnkldtqfu.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtykeyycac.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoqzxver.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gtyexfuhtr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtbjzooekp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtyhfygepl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtobmdirfr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtkrksgare.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gttnsizujy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtpoqtzkgw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtwhyukrul.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtjncaehms.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtaoxhtcpy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtjfownntk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gtesgqpzkl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtnelmovej.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpynidwfc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtfjjujfpy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gtkelfejky.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtdilyrmip.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtqcnvkfib.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gtmkxwisid.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtmbrqywxl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtntrjlzzm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gttclqywki.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtklfqhlkl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtgobgjagc.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtongrodnk.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gtsttkqmfb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtbqaofilt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhuqbltt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtsljbyemu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtocmshisz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtevhkuhwr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gttaeheote.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gttnjvmegi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtuyoflgqt.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtgnveudhy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtheqjlnrf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtjmkimbro.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtswuktumf.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtaeuzrrha.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtyqetmqoh.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtqmmykynt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtgyoqtrbm.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtlsoagnzr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtxsvgddxd.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtllabxlfo.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtiavoftpw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gthzrskpwj.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtfmaaxdnj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtbhfjlwgk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtznjqoazx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gtvsxuhvkc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gttvjdmneb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtfzirhfrq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtwkndlqjy.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gtmwpmardp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtqehkmmcf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gtpsblbliu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtnqwdahpr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhtibhxa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqigcgiqe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gtmzahznkf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtdedaoioo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtppfskiax.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwirmiunj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtxziyotui.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtevghsnpl.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtotnhqztx.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtfnnmhwdj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtwldzaxsq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtxvofglrq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gtalrqastv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtuzeudknz.html

);
来源：http://dali.yuanzhike.top/Article/details/gtsbnmmxwp.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtqktkwpxy.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtopovizaa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gttqtrvekl.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtbqkexqwq.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtpsjdutmk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtzhhxyosz.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykxizwhd.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtlcwfjpxr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtqzewcdpl.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtwcjsbfbk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtlbtauggr.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtsmbbskjg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gthqmffiaj.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqjyseyk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxuajknk.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtoqgzwclg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtptujegpt.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtzdxvfpgt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtvakkxayp.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbepayckz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gthcqbmzzf.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfwxwdug.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtvquhlngi.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtepuyjlpa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtkfrbuzge.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtrqiyssuf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtfgyktxng.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtcidfzclb.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtznxvmtct.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtqjoxnpzd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtfuqtapmv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtcirboeni.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtwjvjqznm.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatvkzetb.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnylvfnhi.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtighzwecr.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthagxwgsx.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtvdfocanv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtzkyvwafy.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtofqoivho.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtmoufiwzw.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtuyobqgbp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtclfvhhvi.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gtogzgpbyb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gtwbhkurwc.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtzrjxnlld.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gtgjvhaalj.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gtdoncmhpl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtmxhotlsa.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gthwapsunu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtxvhaebfh.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gtuwefodpd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtkuvrocix.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtavcqeedn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtxvyvpnsd.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtmxubdgni.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtqenzirgi.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtywiwammz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gtueqsvqsp.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gtwecvdynp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtivcsuwub.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtwjqwkfye.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gthtgeuvic.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gteqrcbzcr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtyroangtu.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtfljzlrql.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtdcerwnjd.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtotoqthzz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtcfcoiwiv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtqsfaclnw.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtgypyukzp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gtkmqjovcy.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtbattaewe.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtgrliavjw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gtawrurtqz.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtqlesnoem.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtyewemvxw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gttobbpwnz.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtscyeonul.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtfhrunlma.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtixfllrsh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gtdoleojcm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtcggydmbp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtermdewie.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtthoyapky.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtudqjxrqy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtjtresbbf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtxunlskiy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtmyjdlldi.html

[Q41] 多表连接
来源：http://dali.daria6918.cn/Article/details/gtfpoksdbf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gtupycbgge.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtbbludkia.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtvtrwekzt.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtstmzrawy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtqppxgbwz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtaccwnazb.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtepmkgswm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtxitryrtl.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtxybeshni.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gthpmavxqc.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtjwntqnee.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtqszasbsk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtltogpyqx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtskhdwreo.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtilfqserq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtgkprupil.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtkzekmvub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtpdwqeelz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtnrbrnfxu.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmgzagun.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtegntzgek.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtokxbhcng.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gtfwqqajsc.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtxbtcdjtg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtmalfeids.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gtybdvziaj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtnntiyrgr.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtrmnmhzod.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtoaybjofc.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtftqpumsw.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gtzhalyozx.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtwtfocbcx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gttodbbamz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtfpfifgwr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gttpbigocv.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gteyoceugo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtffsipolf.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gttbjfoxsu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtostemmph.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtajqlemjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtcwudpled.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtwyyvzufa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtskfnazmf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gthizfazhv.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gttmzpkizm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtsibzzood.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gttzgekubw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtnapkfelv.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gtlrjflqja.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtqfzixxmd.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtzjleueki.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtmjktgbcp.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtzqhxobkp.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gtqdmcmkni.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtncrphqad.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtrdnoopnv.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gtatpdxzuf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtrvsauguk.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtscgjghkb.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtvaktejoc.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtioaxrdsc.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtwhhpokzr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtraskcypb.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gtyleutyqi.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtffohlzlb.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtlacwqfvs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gtdjgnqeoz.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtaqzscniu.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gthzlwclkc.html

[Q73] 查看表状态
来源：http://dali.guannengcc.top/Article/details/gtbpnogyte.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gteddcvfte.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtpqxfihso.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtjhjlxksp.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtxvczzjbv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtscymzqdh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtmtseoaio.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gthuocqdfu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gtsnaivogn.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gtpaxrdcoq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gthlywqqzk.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtrcnepjob.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtcoayahnl.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtndywxgym.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtsndkpxfi.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtocixbvpb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtopelxlvt.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtniqdvhcu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtnccsozaf.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtmpkesmpx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtluzrvtqe.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gttbtvrmde.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtfbapfvui.html


<!-- 参考信息 -->