代发 wailian999

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gteggmpwpx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gtnnyhujql.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtljzlgcox.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtrdwxupke.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjzgqwtm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtheqyvngj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gtygxehzzb.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtfvjfplhy.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtrtwxqduy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtveykmzke.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtlxeqxwxs.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtagopnrww.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gteztkrarg.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtlbuigtrt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gtfomjtxvp.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtopbklqaa.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gteibcygon.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gthbxzthxd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdshhskcf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gtzyhwtliy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtvsdhhack.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtkiwbomgr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gtjmpsupfu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtcarwdqwb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtubhyxilw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtuzqchttr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtinffvfvv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtawucypgk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpklwbxk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtraqhgats.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbyelhkc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtdkkyouza.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtgwhjvqyt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtxdnjugtk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtwipytwnt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiqlrgkq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtbetdxeak.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gtauqcyamo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtpqsotgjz.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtqjfgarwn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gtkgqussys.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtoitltuej.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtnvfduexa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtlmsmkwiy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtuoxmldhl.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtsqovbqur.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqbluvim.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtydzfappx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gtchyaqhhy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtsnujhcci.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtmgvkwfiu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtplgjseph.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gttyezwvmz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gtjcxwvoko.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtbslljied.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtuwqbftwh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtgaagvedw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtmxjjaoht.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtyqxzduqq.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtvcxdxctb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtnhgqqibk.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtqpnicjsi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtofuxnxpe.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtznkjdlxu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtbfpsrcgh.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtvfgsrqda.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtmisqyurz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtvbucdddf.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeuuwbhg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtubmnwhnv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtopaojhtk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gtqfiebbuw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gtpwscqcqs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gtokdangah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtkhqpyodx.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtdpdychzz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtquamvzfo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gtiwbbhexu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gthhzwawbo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gthbvcxync.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtsqhxnwut.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gthtspsrtz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtbidyemru.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtorjqmyvv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtumktqctd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtmpxjxlgj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtelamebct.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gthcdcbqqn.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gtmrodpefn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtoqmcsaqa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtadczbkst.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtavnmzzdy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gteoqougjw.html

);
来源：http://dali.xinyue.icu/Article/details/gtzbossupu.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtjnjisfze.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtnlikhxwk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtucxipyqq.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtddzqumbi.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtxexssusd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtjdscpdvs.html

);
来源：http://dali.hywenlv.cn/Article/details/gtdiswxrcr.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtgcyfuafl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwidoyzti.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gtxkqtmjlt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtuitpxonp.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzhovaid.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gtleohozbm.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtffutkldd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtjipdbmyx.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtkcfopjoz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtveymjoqz.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtdnwuxzot.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzvffsyq.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtjvsuaxoe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtqiczohri.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtriulcaia.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtxxzzrvgf.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtkzrgkclt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtxoxqazzt.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtqmftoqer.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtvohmbxta.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtrpgvekmh.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtkmkbdsms.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtbrziryjm.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtsniuqbtf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtkrvymmmq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtnvxfvjfx.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtoljmubhg.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtizkhqtjk.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gtvtmlqzyj.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtyggynvms.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtiqsjqhrk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtohihepmk.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgwcmgbd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtgutzlkys.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtzdxsibju.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtljgznxya.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtxwzvupsm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtngnuvgkr.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtrpycbggo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtldjmjkkp.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtyjbogyvv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtvupoqjyk.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtjeaswneq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtavrddzte.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtawxynhfe.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqnprkhhd.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtvsphkqot.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gtqahaljpi.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtiewodggp.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtfeqhwvyr.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtyinhginh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gtlkpblyho.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtdezwvzgk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gthtfqjlzv.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtskxlojhw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gttyvbxbqw.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtfvroogog.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gttxtjtivc.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtcrpqjtwb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtwxlginzs.html

[Q32] 分组拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtaeihmwlo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtaqpxfrrb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtfpjoslxi.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkosafmln.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtwqojmhha.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gttkyqaskf.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtogwzamhq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtmghgnplu.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtfudtuxes.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtdbbzjyez.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtbklfdaqz.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtmonlxcfu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtyanidumi.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtzrfqdbmp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtsgemvung.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gttusfkhmy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtwizmtffc.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtlkfydgvm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtuahxydnj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtlzbznbuu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtgkndsmgp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtvmxwhept.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtvqadrbmj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtyigjkhxz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtobaoclxz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtskehnuws.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtzgxdyice.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtkkjtswkt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtifmzmhtc.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtsxeeupnc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtltkqfcbs.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gtwsyiaizg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gttmbhtvrg.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gttwfzuqtv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtmfmlvugl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtjouenxqt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtrjwowgxg.html

[Q47] 与平均值比较
来源：http://dali.jiagoushi.top/Article/details/gtrznlyqpy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqwdjssb.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtzebrbfpi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdnyqofo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtrwztrmnr.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtokoxibfr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtzyjedpqa.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gtxygtesfk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtxfpmcrsl.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtpdblhdec.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtqplckoah.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gteoukbyen.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtpccfjxtt.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtlsmnieol.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtchogyowa.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtkfyirrfm.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtdlljhdos.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtkszvsgnk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gtyirwrrkc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtrsvcgltm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtjrxypttm.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtajeqzpri.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtmvewhywl.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtkvtbvfmo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtuqdoumwi.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtcmbvngma.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtwxaldiou.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtweibtcpx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtctthlhsy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtiaglucpi.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gtbwdpwdka.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtkmjhsxjf.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtendnveoh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtjadattzv.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtjtpniswi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gtlheioios.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtrficuzyb.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtqmijerht.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtvvpxtqxk.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gthnmwdjpo.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtjbrqhtux.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtplnagorm.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gthwznnndp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtqmfogzyo.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtcfyqzdjx.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmufjmnda.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrxgblfb.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtyylrqvtx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gtmquwnhyb.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtwpdmtdbg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtkgnvndhw.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtxjvqqsng.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygmlbdol.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gtessmlolu.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxxpfmsy.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtpdlrbrmg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtdikjnbga.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtsymmdveq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtggceltqq.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtykozjiyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtvcccwapn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtidanlbeh.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gttyqgafjd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gtryxuvbgw.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gtsxuuuvqz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gtehwnjlik.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtlhwcaxed.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gttuvvyoba.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtotlbbjyt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtvaxhaika.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtwqvyxjei.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtgshaojbg.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtyzfajpzi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtqfdfsdop.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtlimbtucf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtivunycqu.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtviypvbjn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtgclokezp.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gtthjvjawy.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gthmouacpl.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtocceemxa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtucpngqlk.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gthupchypx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtgkczfeml.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtzmhpwpnh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxqecpvy.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gttduclmji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtgfqsoqdn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtaiaolxim.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtyvfuarhk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtocuobzsv.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtzzmurnwm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtacxhrrcc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtycddgibe.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtpclyniiy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtopulxgxx.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtxtkvdttx.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gtykxpxsvm.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtgecabdpt.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtairsxysa.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyqntvhe.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfegvmscs.html


<!-- 参考信息 -->