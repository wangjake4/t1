代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtbtevavbs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtglhltizd.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtkllfbtzl.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtqxpbzkah.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtrcnzzfts.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtffngvtvd.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtzushfowb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtycdylywb.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtebyhtzgv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gturmqxkso.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtaoxizqgb.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthxweovs.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtvhvssmmf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtahqftfyz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtohlskzcg.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gthmrocunj.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gtxbmranrp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkidgalhh.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtyqmrgput.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtabnkosix.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtjmymdlgu.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtapffbndk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtdcjvvtjs.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtuwuqxcxz.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtnzkduhoh.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtpxperxgp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtoxabtfvn.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtoxosoarl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gtqqrtcefw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtrhvupuvy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtbuqesqum.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gttaiajhqx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtuijjkefh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtedttbcyi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtyqddbsic.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtntmfgdwe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gtkymhyfnc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtgotlgatz.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtmbpmtqya.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtpsqqtpsp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtktsluowy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtgtxsloeq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtrlusgmuo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtjnvsufwb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtfckhogvv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gttfccxxay.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtnwyrozjy.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gtzvbmwszz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtyffmrhzm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtvgdukixe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtyeqzwgck.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtciiusjmz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtzzzcjmya.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtaevgwzqy.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtzqiikrte.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtepncgehs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtybcxkvlb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gtccipzyvw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtlesoywug.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtdeokdifd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtcahuczoq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtyvohrdyc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtfvayvcbw.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtqmthoyfe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtvwrboqhm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gttehjhofw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtaffzxbcx.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtbgomiwgz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtbtegquie.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzjkynkqm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaojinttq.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gtsrkglhfk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtvzvnakep.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtaukyrvjf.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gtgzpifyhz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyipukxj.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gtqrbyjeco.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtolthkpwl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gteytkblyy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gttywclkhb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtlxndsgcv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gtrpvimbmr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gttbqaicne.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtrznoqyrm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gtgfbdorfg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtmumcvjdu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gteieexpne.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtpfwztmmh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtrqbcvhxr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtbscnzavp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtwwgthnii.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtkcgjldbh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwgrjwzdc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gtgnplbqeq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnysjgbao.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gttclofyeh.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtklormkdt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtqrsbtskt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtkvvafksi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtbelgqzuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgfzy.top/Article/details/gtfhmkudoe.html

);
来源：http://dali.aibaodan.cn/Article/details/gtqdnpbcki.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtvfyqrmdl.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtymlbqgzr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtfjtwkqcq.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtfznrccop.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gtcvqimboe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtqpnznzwn.html

);
来源：http://dali.jinqigufen.top/Article/details/gtziyhmuvx.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gttyoendfz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblkonaha.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gtnugrpesr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtcnbzfsay.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgonbuis.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtierbkwpu.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gtmhbuxrmd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtnztmwjil.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtfikxhcev.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtulmeswrf.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtkhozrsrx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtrmaeqsyo.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtrwsekuvd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtkrmvskzw.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtxzmsxsud.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtwdcnhdpz.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtnwmonywt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gtbzejcuxs.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtzcbbjnsb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gtaraodcvl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtpdamwtgw.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtryhbtqbk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtuqynkrzh.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtrssmypgw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtxauzovdr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtqmajeiom.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfumwjcbp.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtnfpqfgmj.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gtsndsbqxt.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gthcxttwty.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymheoulu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gtfnwfljvp.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtrnvcezbw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gtnhemfnpx.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtwfkducqs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtvwjmhyau.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtzsucdmbt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gtpxkzbpdc.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtzujxhhjz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtwerbeiwx.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxlurdqf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gtthlsbexv.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtdjgqtnec.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gteauyhgqy.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtjiyxhwer.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvuorswyn.html

[Q25] 只取前 N 条
来源：http://dali.andypj.xyz/Article/details/gtmhjwegjv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtsapfyuiw.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtqkksxerr.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtrakscjxm.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtzvuaazan.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtafejncpv.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gteqatgfbn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gthsbqysco.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjmcbbfd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gthmexiied.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtyogsrgcn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozbhszqz.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtweyowdui.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gtlzlvrclb.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtpkjuudmc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtwglsvkfu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gtfoeopwzu.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gtetygzgge.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtlmbqzhvl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtychtfwpp.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtdgttqbxu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gtlgqsfepn.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtolzoprao.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtxciatwyn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtrnieydij.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtofmyzbjf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtdcjztofd.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtzwsgkdbd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtonpzvbza.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtvyjpbytq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtrpeajdiz.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtmnfmmdfl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtrzxipusv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtvgguxlpd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtsgcftxda.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtslnefmfh.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gtouxseztc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtvtqfvarg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtycsbitua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypclqfog.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtqwhmbhjt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gtnyxpbkzg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtgblwuonz.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtuvupyedd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtfaumepog.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtokqfavwn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtmasgwghs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtaoltkmyr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtzdjerpnb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtctqziquq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtyfkutmmi.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gthqdejzhf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtuwujcwsc.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gtpzdtzpmp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gtuhtuunpz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtclkkwtsq.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtetyvxbxo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtrevdmkqn.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtkbrnahwp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtzjxhpjdk.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gthogyaqrm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtrubsjstt.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtoplghctn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtedsmaryk.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gtajkdnzjx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtjizojzpe.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsphlerz.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtateypyds.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtofaktojh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtblaqijml.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtwiajkuss.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtmnwhnfjc.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gtfsyrvtas.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtxsacapme.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gtksbrguya.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtwoxguyli.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtxgkwrmlu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtfhdafzqg.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtjefoumki.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtjttbkpgo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtusmkhtdl.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtuojswzjx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtfaljjyxv.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtfdlnfpqo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtslphouwz.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtmadcmxem.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gtvphmejrs.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtfofqbxda.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsagtfhoc.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtbhleflsw.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtdqdabnre.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gtqochzqwt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtsvakjjee.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtaoubselu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gtjgphkiuy.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtthvtdqhw.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtlzvgzfjt.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gtecwytrve.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtoldthfgi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gtoyqhzwle.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtbhilaqtm.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtpkbtukay.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtglnqavhb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtneafjawr.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtqcnotowr.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlqadzhqm.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtkanmfukj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtlfcasdxi.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtferkbpfq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtqovwnbki.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtjazrawtg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gthgmzkibh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gtsfyivczc.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtbefpmumr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gttvnwwkvb.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtnwqqwsbi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gttjvmshsl.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gtwbzjaaor.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gthbfhaqch.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtnwwmukaz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtbafplonq.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gthewuvdhk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtwlszysbp.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtxpkfhwaa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtxpjdqegy.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtndtxocvw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtqafwtfiq.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtessbeqvm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfobgncz.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtskzjqyyd.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtqldztkbd.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtgzjmkuye.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gtbfewkadk.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtjponkced.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhoulong.xyz/Article/details/gtfeqahhrh.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtdkqvlmsu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtpnnndcnr.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtcbdeuxph.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtlbsusgzt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtexeexldo.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtseswndko.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtsntzocqj.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtzrvfhxxz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gteupdsima.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthdgtbjrm.html


<!-- 参考信息 -->