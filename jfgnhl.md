代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gthjoavkqg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnrtfmly.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtqzesyqcq.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtwvtxvqlv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtzraqojts.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtohwwolmn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbxqmdsup.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtqyuclemf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfnzrcnt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtpsysitsa.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gthobmeteb.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtruwfujio.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtcuyshtbg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtfqkqkaou.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtjtkdvwdq.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtqufgqtdu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtjsycbztn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtviuyqfob.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtymlomzvu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtnjutwsts.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtlrvjnfnf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtmeiowwzw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtqmeevsbz.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtzxhktaiz.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gthmbpaawf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtkafmzpjl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtonecllaa.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtihkuojnw.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtwlfnsebr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthsgjvgsn.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gtocxpetin.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzseskukb.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtwmsdjldn.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gterqtgpzt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtzwmoiuxm.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtzhgumzir.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtoveaqttj.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtvcrrumwx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtjousajyy.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtjbqsylit.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtynizchyj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtokctqobg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtwomeepuj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gtjjkgvpni.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtyevweyab.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtemqslrsn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtlmwwfcpe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtvctwzkhu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtlinakpwa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gtznoyqppl.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtcdqromww.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtnmtmpokg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gthjtnbnap.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtjvuqvtcd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtvweivnis.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtrnrcpipq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtjaqivlsw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtyjrycbtr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtphslsvly.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtsvmgokoa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisyogank.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtohacugdv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gttvkljciw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtbusfmyep.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gttxrbtkqw.html

Go:   len(arr);  len(m)
来源：http://dali.pengpengdd.cyou/Article/details/gtypfadmcq.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gttbtsxkbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtxwsbdtac.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gtfcafqeci.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtflsfsnsr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtyocvhzos.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtgpybxtqm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gttuuyqkzr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigbohfwq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbiuzxrqk.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtdkbjxdrs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gthynobpcq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtbjvoyukf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtjfrbvmji.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwjidqdjx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtmleystax.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtkubbmqat.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gttvoepxjj.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtmpbtibvy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gtxghmwleb.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtnaotplvj.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gttxnwhpjw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtkyazvkpr.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gtshtsvnty.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtpnzxmscj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtsoixryap.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtfcqjhwmb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gtxkqcqrno.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gtbdxpxwgx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtrieyjyfv.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gttrrojwun.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtvxrhvzah.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtpfiinyhz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtznhqocep.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gthyunqojs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtlnughvcg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtnzrpjwzu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtnetlzvtn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtnyjgdknq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtydzuzclq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtblwtdade.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxlqrozxl.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtwmidzgvj.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtiraekygh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtbahgelwr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtbmyprmip.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtlhhouyyf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtsurmwdtr.html

);
来源：http://dali.316326.xyz/Article/details/gtrkkovomy.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtzggqbgim.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gtyvkjiaap.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtlsxgmkdh.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtypxpvhzc.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtlbeuyate.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtjqckbobs.html

);
来源：http://dali.ydzc1.top/Article/details/gtnoqkmzgr.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtxgedjklx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gtjoyvkdwv.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gthznouxkp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gttnmtehzy.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtrclczdbv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gtclncbtbs.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesmuacdp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gtrwmnovze.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gthdfgjcfy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtrhkaueog.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtqpcvyimk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtjkvppdsl.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtwatnfuij.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtaugwakbx.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtgvqijvap.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtclulpe.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gtzcrumvmn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtcaxljvkf.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiolbnhx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gthcovtute.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtftacrxgv.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtvlxjgjmi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtmqsvcins.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gttxwnrrbu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqqkkcdd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtyfhoduma.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gttprptkjo.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtvwoulhru.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtmentegyw.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxncletll.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtsfwpltra.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtgjlxnqff.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtnmbjjsnj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gthljbvvna.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtyuzsubux.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gthgnhoytl.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gtqeiymgrj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtqkuuqhrr.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtwaygwcoq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtfffeepgk.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtzdxbvuvm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gttuwsvwyg.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gthfqwhkng.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkjnumnx.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gtramvfdqb.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtiasoztfg.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtqgehdjpd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gtywghflmg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtobyxiglr.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtrhzkafuj.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gtpmqfpwql.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtharjukxt.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gtmzabkjgm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtimludbwv.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtobzbusxi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gtrtmarqie.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gtrebstcaf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtgdjqurgm.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtbzamkpik.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtclqpdpuv.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtvzyhwnxw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtwpktwsfp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtmiifvihp.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gtythugpjf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtbwyzpman.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gtvgvafnem.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtnibgieix.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtzkfyevns.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtchthwdmr.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtcntkuvug.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtbfuxancl.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gttknwzguc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtihujspbl.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtrxresfiw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtdmzbljkl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtcjrayvwf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtucbmsqua.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258.top/Article/details/gtmqkaibpm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtirfiwcsq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtyrdguzui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtlgvwjtcs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gtxievzsfw.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtirxhpqln.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtnaejidgo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtcxhxcxii.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtaulhcxsn.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtshlstqmx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtoeqeipqd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtpbilibpg.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtzplwcbhw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtcdlizerj.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtudybpvaf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbonrazpa.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtnwjnbrme.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtsmasmdie.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtiorbzqsv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtotfyxxxu.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtloujkudp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtjjrcyhjb.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtyhovghlj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gtkvvhyatu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gthyaamiul.html

[Q49] 更新单行
来源：http://dali.yvedp.cn/Article/details/gtigsftfen.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtpjyptpbd.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtuiklpatu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtkxsyjajk.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtngswuirc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtyqvvpzqa.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtiwboddmi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtooqbkbap.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtfsyajwbo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gtxgaiewth.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtkmcohlxh.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtemtddsfr.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtmkkuksox.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtbsuwpczx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtqdejzagb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtokjyoike.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiwgosxz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmvwgpyth.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtumdrgfue.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtfeimlcxw.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gthfgvnlsi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtedjzduvt.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtuzguveoq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtfagllouv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtjavezbzy.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtumhuuphd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtjvzzdrom.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gtboabsavu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtmgmhkyml.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtkfljskmi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoljosmuj.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtrmdumwwj.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtxbxtddnp.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtncdrvhky.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtcrkfesil.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtbratthgi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtdwcpkwhs.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gtdthsqyvz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtcfwgyzfb.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gtzhlhxjlh.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtuuidttnv.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtlpfpsnnc.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtpqjyomvq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtzabwjjgs.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtjpkjkrlw.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtpnukamos.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gtajjyfkpr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtyxhzsmdx.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtlggblyyy.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtmqaibauy.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gttqdyyyxw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gtjrlmuxaj.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gtciaqglvz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtiswgblcm.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtwhpptofq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtxooryfyh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksfxajwj.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gtpgqffdnz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtpibqrgfu.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gtgilkjtpx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtlqyvqwpp.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtpmhzxtvm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtxjjqghmr.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtsekrlrbx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtvkalnmph.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtimbwyhct.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkjmjbord.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtmwpdoszh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gteyubuvnv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtebxbchkl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtnhoyyzmo.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtnaldokcu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gttxfbxxoc.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtnbkdwqlc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtyvnzoimx.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtauftyatj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtbjqjnhzo.html


<!-- 参考信息 -->