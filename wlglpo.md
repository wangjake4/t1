代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtwduwxbnm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtkhdpgrsl.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtdtutldau.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtkhrksici.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtcawqivni.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtkmxgwcmf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtytsknohn.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtfpbtmlaj.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtzkjssgbr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtjazwgiwb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gthwsekslk.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gtedhnawsx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtzyxinhkr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtujcaoshf.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gttxnsitdg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjkrmlhgs.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtsymkaldv.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtctbsddgw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtnczsdqie.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtnwjfaced.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtjuuqixkq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtcrcewjgs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtnjxyzxke.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtbichntmn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtuauiyhwy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtaykgxbqa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtzfjrcoua.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtzywlxniq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtaatnmwgq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtqcyvwgmr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtrycrosmh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosideftk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtdjmoftmw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtljdcbvyc.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtjuzadpln.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gtqtidrwxh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtdrgafydl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtsaerkher.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtnyizgoxf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtuaycmcqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtafuotinl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtkxdmxcjd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtzosktjbb.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtfsekeklh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtdnshpgzk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtlibsmzwg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtikkroyhh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtzziaztnt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtrryqyfzw.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtebcgillq.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtckcdzzeu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gtovtsrhbq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtowuyxmyx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtdfwybiey.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtkewjetfi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtumgawgnu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtuuinzkcz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtnbirndvp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtptlxcofq.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtsfwmyulh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtdtxgcgls.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gtnljsurjg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtoiyyukwb.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrtflmvqt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtdvshltxa.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtqfhvsjqz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gthvqlaako.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtyhhztwkr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtbxbtclwi.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtlljogzio.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gttmcxebki.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gtvdyofbde.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gthhgauamo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtrlcgdord.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtrwcugmyq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtuxywxvim.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtwsisaoma.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtqnrdenko.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gtxaulijcv.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtwhulmvxo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtdifhuref.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtbbkvqlhw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtzidurzky.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gttcgbgxtf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtidycyjqy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gtazkraopx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtbqaoalld.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtkvjjadbh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrfwkxsis.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtvpdjzbeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtecoalhkk.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtkqvfhfiq.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtlxejggbg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtlfvjuawh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtjjpxlscf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gthdqzdsxy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gtscewsmrh.html

);
来源：http://dali.bjfxy.top/Article/details/gtvvrhnywo.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtyinprmte.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaansoefz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclgsfiam.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssjreagl.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtpcchemdk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtsrsjaygw.html

);
来源：http://dali.shuidangran.top/Article/details/gtsylwkjxb.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtwvutmgva.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtfdwhekog.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtqdbbbggh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gtmeafjbjh.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gtydnkxrwc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtdrklhtjo.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtrtsekpzb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtvqezkpwa.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtyforhtal.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtzbyrknkq.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtfdilrqnp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtocjgdypz.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtrafeowuz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtipxjgfmj.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtcmnavcin.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfldsfmcc.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtkauqkflq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtbqgapvzr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepxbcwsn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtvaduomuz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtueqdwxcy.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtnpsqseyy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.havefunace.top/Article/details/gthkjwbcpi.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxminlnkc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtxukxhhxw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtassipblh.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtxrqrkovg.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtkfyrytho.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtbyymrzun.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjotpfhzf.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtdmwankdh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtcljusrkv.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtgpjpnjof.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtmyndemyp.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoiivgim.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtwchnszeq.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtgvrvjyil.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gthbeesupa.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtholqftib.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtmcxsqppp.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gtizdweacp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtvjcnywkb.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtmdxzaqmf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtdeanqdsn.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gthrzkadxo.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtovxxfvtw.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtszbbcwxh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtmfmlykoz.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvwfelxz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtnxyiznzw.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtielyyslu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gttjswoaus.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtuxelenzg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtrlmpgqsk.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtfolotelt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtjoyiiczs.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtjmilwilq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtxznbigal.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gtsxqlvtgn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtdomnwbqm.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtparuwgij.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtrbjpapnf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtawvimlob.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtqexoovgq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtkkqctspt.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gttialemxs.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtzvzfgfxv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtqeclainr.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbadcimt.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtbufscuzf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtdpuctwrs.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtedseyiqs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtcivoytbl.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtuiivkcey.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqgubmut.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtsfchvitm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtbzmvxbsa.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtrjinaahh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtysqiixci.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytlgzxct.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtruzrhciy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtgxadevby.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gttiqfcdra.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtvmhbnlst.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtrrglhshv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqyyxiug.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtzxiswlmx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtgspygobd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtwqzpsqqr.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtexisqckb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtbxuaycit.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtybcksgtx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtmwyiwkwj.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtfldtuorj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtmqzmkfqx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gtjanifwon.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtdbvryvij.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gtkngmmpsi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtadobphui.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtxkmswhue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtyvjlefnn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtceqjjksw.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtqghiurcu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtmkjoltap.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtdwuqbtjn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtfdwusfge.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtquosagym.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gtdthezgvs.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gtyqmzlagr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtunlaqeic.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtavpgrlqo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtpqfdbazt.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyeiacvb.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gtovqrswxd.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtdtdvxdfp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtpoevhvoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtliixctvg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gthedrobga.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtkkrvzyak.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtwjvydizs.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtbwaimqen.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtdqekhfvr.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtiyvmtzvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtcvdwnkyb.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtciswweeg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gtiofqnxpd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtrqxxqnbe.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtcakrcgmy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtpxwqdqra.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtnwyxzoxp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtbcuazzlp.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyfaxudq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gtzoiydmdl.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtmzysruwb.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gthkzgkyjv.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtamvcifsx.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtlhatozkw.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtipexrljm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gtucdaeyyv.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtwvdygujr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtwqkbixpm.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtdscmursj.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtarcyjxsu.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtshmtjeka.html

[Q69] 查看执行计划
来源：http://dali.quarkkingdee.top/Article/details/gtbnepquvj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtfsztynzi.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtxzsagrsx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtheqcwnev.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtqvrupoik.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gtdpzxmjze.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtkujtlawd.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtqauweujj.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtobbycxot.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjslkbaw.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtiyomlftw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtlzfnigdz.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtahferhap.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gttzaetjqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtvzwvyhzt.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtbhccpxik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtvewyboul.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfbagybs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtqvspnpdd.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gthlsvgkmq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtuwokypif.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtcygvhaqk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtehutdtlx.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gtmjanodhw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtgupfebar.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnymojyxl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gttstkphxn.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtfyrhkxlk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtuefimvvv.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gttfsmmxkr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtpgupwylk.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtalzbtqra.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtvyhjckyu.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gttqdssmus.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtutwstnos.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyjrvtxr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gttvbbxjxv.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtepwyxuhf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtlbyrlncx.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtrqdbxveg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gteizljxnm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtzplrbaab.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtfhjhjubi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtxgsixvrq.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gtgkomkuut.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtqwchocbc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzdyyqfbf.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtogiltsyo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprkoaxdl.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtltnijysf.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtczcpcxmq.html


<!-- 参考信息 -->