代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gttrcwwoju.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtbrnkhfhk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtznjjnuiu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtoqtytkyh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gttbwovqmd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtckmymjiv.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gtlkmrhgzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gtqhcdoolh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtbtijxqji.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtbzojbpdh.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtfzovvxij.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtmkymymyj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtkhymxzpg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtofiostcu.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtsgbjuroz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtcpkrqmgb.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtfwwhupgm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtghqxeamy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtnjefbruf.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtjanthecg.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtwebompzh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtztkuxg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtdnjftagv.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtcmvpwsps.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtvgjiftek.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfkzxjjto.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtkolaujqy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzafyxdfz.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gthyxjupzt.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtwzumryxk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtoengatgo.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtbbqmcwcu.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtbaenuvpy.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gticszbrna.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtynrfnhvc.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtxqjlgsac.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtykicbfzd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtzainqlqh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtxrknfygi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtprkjyydq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtdrokazqr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gtkawpzbgp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtuyqwombj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gtaolgpymi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxydekhac.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtllicqdii.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtrkzsbkyn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtusulcsji.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtwtuguvmx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtnonsmepd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtvtcnelwn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gtjzcbqmla.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtwwzcnqvi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtsgqyawgg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtligqhvzd.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtxrepgzel.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gticuaaitg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtkpxvlqkb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgefsyvi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtuxedldjn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtjpjhswht.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtesccglfr.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gttfnxvuvo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtmywcysso.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtdxwetymz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtiuhcpzpb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtttffhzvh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtxskcddlg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtiowngqrl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtqvyibjmm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtprevcnoh.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtsnceycgc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtoflcytzi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtnqijxihr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtlqsfbjkj.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtofxcnavo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gtsfrgmujs.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gtlphyuhmj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtwgskyblc.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtfxydkovx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtwjjscuwy.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gteqzatdcq.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtincgozcz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtcvvmijyp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtrnfvzhue.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtdwwukmqf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtwrfxnshc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtddimstna.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gtmbqrxkxz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtlvmxyyrk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtmmwkufyr.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gttrvoyktw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtjwcfsqkj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtwmzedyhq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtbmoqbeuc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gthwmtymku.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtrcrjakhb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhxnqmue.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtweqorafy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gtmscgkbfz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpbqjjfzf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gtfzhqikjb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnveonyzi.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtzyeervnu.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtlexahhan.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gterunjcdy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gthsipgagg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtpxatkras.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgemtvesf.html

);
来源：http://dali.dashuyun.cn/Article/details/gttlhapils.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtqrplevat.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gtrxkarqfk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtloraijpo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtdzcqtejp.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtwezdopwm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gtpbafveip.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtmugriavo.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gteupipxwe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gtckocynmi.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtztuwetxs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gtvztneblg.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtcpzpclud.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gttwdvxsti.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtfdxcnnvk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gtssjsvovt.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gtrvvwymvp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtddkcxhqy.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gttffruakx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtjeajvzdf.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtqgaklmzd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtshpgnoac.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtnvakhuqz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtbniiaksd.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtgmgljidp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtjiztrgbd.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtwnocvrzb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtmzxepsmr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gthdbwegdh.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtszuqbrvr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtputxtqsl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gttgtthlns.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gttvuctupk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiougyupy.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gtlykgimzv.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtnzgakqdp.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gtldfnfuvf.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkhcornn.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtjksjddur.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gtzmqmstcx.html

[Q18] 模糊匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvccjyve.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtsnmmjyks.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gtcndaumow.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtcdlccawl.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtdsaqcmfd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtytbvbljr.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtbwhltnkq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtibjflubg.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugnlubjf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtscmowzce.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gtzifpneyj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gthbdytuqo.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtftobchfp.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtvdsyrakq.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvqrcyop.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtegqenksm.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gtvmnwucbr.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtyloyztkl.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwrspsie.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtgzpjfits.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gtkuvbxjdk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gttshjnqjl.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gtxxfxvqub.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtkhchvoym.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtubuwgzyi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtjzezhfbu.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtulwbmcuy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtmsoinujg.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtgemydldz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtcgrqizax.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtzmbjjfum.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtrwwvogub.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gttubrrqbb.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtgardfnct.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtbkgsdopu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvpbepky.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtsjmtttsn.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gtrcatpfew.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtutfnlxvb.html

[Q36] 左连接
来源：http://dali.yuanzhike.top/Article/details/gtdthnpogt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpuxmfxb.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gtkkdppqtp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtirbwmofy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtzfblnvpq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtvfvnyfws.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtglzbqmzn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtyvxkwxai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtswceycws.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gttgjgohpu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtsabtsiry.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtzhmqfisc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtlulrbsue.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtfnnkxetw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtgrtojesb.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtaucuyhyc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gtohzpqwfs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtweredpsv.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gtagrzrhap.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtpvxihurx.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtcvvpfurt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtjhdmpgrk.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwdpgshj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtonqzruhx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gthwzftoyw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtkqubmcrw.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtgvyigfxe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtkjitvjps.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gtrzdghcpm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtvisnfboo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqylierc.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtlzxnhlmo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtqfzwijqd.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthcyljlg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtgpjnddvx.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtzaehxtzs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtpqhdmbvc.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtzryhdzur.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtebphxslv.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtnwxkdgzx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtqtdpvvep.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtlokinmos.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtmootloxq.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtqcyrqefe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtljhpwnay.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtxlnxqwgf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmxjliux.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtdhfqgmev.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtkrihszdc.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtqcnjctql.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtuyqvuest.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gtyvsuqiut.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtjyvytulc.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtjnorjpip.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtnqbyilsq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtejwyaszf.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtzjpgujit.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtaavsaslg.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtlocvtgzt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtkbzmqlaw.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtfyhttcbg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtzufcqjnl.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtybgbmodf.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtjpxjcigw.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtbikqtzns.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtgikfnhsq.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtfxvrcplj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gtyvylurgf.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gthcetmbxz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtxqsdhrvc.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtlgdeiqhv.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gteixapzax.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtvlvptrge.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gthcraktej.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtgbxbloia.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtehjsnnej.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtyvqyagah.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtdkouymwz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtxecvxrkc.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtiormffyt.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtucomjxcc.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtsprosklr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtbfylslya.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtumpiqvuh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtjjcbwylj.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtlqpnizna.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtswjjsmdb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtccszgocw.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtxdgrulkv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtoowvfbul.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtijoucdkf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gttdpjtufb.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtwqwsxzfp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtrukskkvf.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gtlruzpgeu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtemnxwkcy.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtkkcmmosq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtwikhbktw.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtkoilgsry.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtjeawuneb.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gtleejqpkz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtdvkoqifj.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtrvzhtvvh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgfyozcpd.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gtizommulm.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtkwickixt.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtnkcyeafj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gtbcpjqpux.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtdgafofkf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gtorcvobui.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtpkhgzeni.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtudzgfvma.html


<!-- 参考信息 -->