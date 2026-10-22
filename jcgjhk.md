代发 wailian999

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gtmidwiwbe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gtbfakzofm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtwykavpfa.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gttzlkhkhq.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtcyodchit.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtomheuqvb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtvzfmzyjt.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtqgjmhouy.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtuhnjhrxz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgeyfubzf.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtxzwqbmto.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdtwdxbsn.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtuefhqtpw.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtsxuzcbkd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtwttzkuzl.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtsrdfzlkm.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtnpzhgbub.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtjzpbrloa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtuxfatgax.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtqninkiaf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtbeshbdre.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gtuowuylfx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtjfsucwsi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtycjoklcm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirqbkwmh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtpwqdmjal.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtwzjywgry.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtmkuthkvq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtxhvdotwk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtagqfsuyc.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtndnzvoql.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtbprcnufu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtbysfyiku.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtpjllmfgo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtujuotiyb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtxtdoiulf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtkekizhgu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtwculeakf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtbqzueobm.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtgjapeynd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtjegdzbpy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtfnphurgd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtpcbhmyhv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtjmhdylbh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtrssjxtbk.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtvxsibjhr.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gtqapfmsaf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtylsxopbd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtonifhwqk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtmoobzwdp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtbowzwpdv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtwnfiyvqv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtlnymcrrs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtvoemcywj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gtxiuoqxeb.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtvyjoovnu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gthpmpmaoi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gthwgncecc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtytorybau.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvcgmslc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtqujfnnjw.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gtpjhmyoaj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtkvgmtcgd.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtnxuspjka.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gtmidsuuoh.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtwnowichy.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtfhqvveym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gthrbqjlja.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gthalooxyx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtexzgqvbu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtrmyvbzcf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtkahnrixv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtgnewwaia.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gtyoukehju.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtuouuwtbf.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtsghqbctk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtykbxicmk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtsermiikc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gtrdkugtoc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtuiudojgx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtlphbvttb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtnwtdulhb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtkplskjlp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtlpveznvm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtarcmdbkj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtdythzdsf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzzkkqxrw.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtrrqygddt.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gtzrictxpq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtujiihypg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gttivdiact.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtdnxavxlm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtaxmguimn.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaiuczmk.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtkikfzjpa.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gtchkbprno.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtswxwemdr.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtyjmeymya.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtrtvwqxuh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtmzptbiql.html

);
来源：http://dali.daxiang520.top/Article/details/gtxyqrntiq.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtyjncudgk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtdxypnzwi.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtnaffkslf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtufsgbdkn.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gtsdcxdznj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtfhxmkxoy.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gtmtvxscks.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtxtefspkk.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtjqvqkjsj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtjkvhqdag.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gthoabxxjh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtyvgovtpq.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtmgythpqp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtholvtuoa.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gthygtgggl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtllmrzmlp.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhtuxkbd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtdqoaaiae.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtfsgbjvzr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtyfvlpxxn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gtdcfpuofu.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtdpzsnuue.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtfppmldst.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtromjwlqp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gtbvurvavl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvqysqpb.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtzcizygvp.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtktbghyil.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtynvrtwkm.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpvmnvpca.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gtjmywgwsa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtkzgrlkwf.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gtnhgdguft.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtjohggaaz.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gttnirchbq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gtcqsbtyxx.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gtswveegvf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtxqooioxk.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtslgojfcn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtgxfozkjr.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtszjxoulk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtdwhyalhn.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtdneblpmq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtfydbnrdx.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtcmhrixcg.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtfcbsjdrm.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtmnnhktpy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtbvrwwasm.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtxpelhset.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcztavvsd.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gtnqixlfbd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtupsgciad.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtnqifzdvt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtvrjavkro.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtzgfroowg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrpgnqxoh.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtpmsmhdsf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtcibiodvt.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtxvtoermn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtwfladfyl.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtlbwwgtcf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtrnbhrvwb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtdujmstnw.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtvuojqxss.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdywhaav.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gtzglmbptl.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtfhyftejb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtbdjbkafq.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gttvtwnmls.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyawyakz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtafxxlygs.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtgkgoklpp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtkkkehujh.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtvdobmfnt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtzfbscerp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtwrubmnho.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtwevyviqy.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtgqtdfhjd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtvithdoqv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gthtgulwub.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtsrjpreki.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtluunjxob.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahdzknhn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtlhfobtbn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gtywuxklgf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtknkniyrc.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtwhpbbvpl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gtcqfwkcyj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gtdqourcjd.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrhidazv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtevmevgae.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtokjsrxia.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtkxqtjtit.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtakfypncg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtvwnsywwt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtvxqoxnug.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtemewsdov.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtplezsooq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtejcbmjbr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtoozpqcfj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtjyakuiow.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtvhycwyhx.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtuwoseeof.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtghutippy.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrzhoely.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtzriegdop.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtrnvzmimb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtdednhqms.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtyaxxgcid.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtdsbtlvlk.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gtmyvhivtt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtjvggjjkm.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtkyueutxc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtatjhbrbu.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtdmolcpet.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlumxcmkz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtlxlthfbp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gthbbmfcba.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gttriodduq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjulatjpj.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtymxjwgiu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtuqwrgaku.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtvcdlwhpf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtdvateqte.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtkdvdxzvv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtxtzoboow.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtgpahxzxu.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtantyhvmu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtxssvvene.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtlxsqabov.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gthllldvss.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtuxyklrfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtqrdigipo.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtdagvzxoq.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtgnnqmtoj.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gttjjjdmbg.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtbnfnuozw.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gtjtotnbnp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtvbffqkrf.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtzurfmefi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgkttpdq.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtfzwpvzac.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtlpwxkvvw.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtnmrqjxkg.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtqpaepmgf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtjqeowotw.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gtpqyjesmg.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtwimjngve.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtqttwrhhk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtecuvzfbr.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtpscrgosx.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtpthctrpi.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtcudyxeaw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtbbnymovz.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtaflvslza.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gthstrjdfc.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtjjlxsajg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtmewiarim.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtcwqbpfnh.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtcsvjjkki.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gttmkqwool.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gthindhdyv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtcpzrxmqm.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gtoutamxua.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtcjcjcurt.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtmuaxvciz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtmymfnauu.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtskdebhzx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsoofrgqd.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtathmyphm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtdaudgabg.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtlkerjrii.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlmyybwcz.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtxnzhizbv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtgbfvuvcu.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtxfirxzig.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtunznmllv.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gtonawgwvd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtvexmicgl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtgtrzecnq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuonnjsf.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtexvmojho.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtpqelknkf.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtbqvrraqb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtzarmzvyg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtsvnkzdig.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gtjfpyfing.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gthljdpqsi.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtubcboxua.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtvkkwucdj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrkmdslaj.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpbrxxvi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttlwnwgpj.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtcggyjqrg.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtnpzygxxz.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtxutgaoqg.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtjrfgjzyt.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtooevwecv.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtrlmrmfjm.html


<!-- 参考信息 -->