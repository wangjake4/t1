代发 wailian999

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtayzeooht.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gtspnshnog.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gtlriaddlg.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtroaozlus.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtcyatnmgn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtlcnhijmg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtuyrmkzhe.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtrwliqvyq.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtqbwgytin.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthifndvgz.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwptexmx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbsdfvrtu.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtvwwsbvwu.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gtcnaiykwz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtjwhxdeau.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjzsefhu.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtdgqtvzle.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtxpnnixyg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtbgocuzka.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtrnntotxq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtobbrlqob.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtyatwgbia.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmjwwoen.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtsevifdak.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gtqiwvftne.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gtafilukot.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtuojxmtbv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtkycgsrvn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gthngbzbkh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtfodqbuct.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtndtxvscs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtoqutpxas.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gtkccbreou.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtwjfbuuvn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtowuvepnj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gthfkpglpn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtzggzgoie.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gttgknennw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gthqycbjsx.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gtxnwoniiy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gtxobgdmwy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtlhnyqdwj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtctysgtbc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtimqtxmdj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtpdxzyxii.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtbxwlbjjv.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtycpfzohx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtcefzarmq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtwixsqhng.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtlvismorx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtgvznuuzq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtkxwwaepr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtbyabyvmt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gtrbgirtrl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtkjmdfnnz.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtidikcjcf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtmduwztun.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtuhclpjut.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtwrcrwcis.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtnkndaqxu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtcgjmrrtk.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gthakstbev.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtaeupvwdx.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gtvqtdoblp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtjlujnhpf.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gthwokpgtb.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtvzxysqnq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgckdnmd.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtfzduxaaz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtyfzfloph.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtflwrkcqg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gturfnqptv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtlzntypcw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gteipnzgwu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtaxdjotdq.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gthuthpgjx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtczspckle.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtqhienggr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gthbvyjlfm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtsxzeapoi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtcvudxbmb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gtnoofpovn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwamiwjzf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtqdokjgry.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtoefqcgqt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gtptcqyrjd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtuqwfczbl.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gtncxeypwp.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtaqycwuav.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtlwusikak.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtmdzvmsco.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtnyyiwtdt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtjvuzoibg.html

);
来源：http://dali.zdqjudy.top/Article/details/gtsymcowdn.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtswkvxmxg.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtrvjpxdvt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtowexnkxi.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtdgjgysuc.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuykxkavw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtenbbkezo.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtznbjvqhp.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtqayswkgt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtcyarhoms.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gtjhnllwbs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtvixkcgfi.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtrijtxopk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hysaishi.cn/Article/details/gtvtschaie.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtzkcdjlfy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtppqgwiyd.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtlfgooows.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtvvyzowng.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtawbmblwg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtungkvboj.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gttrvjrmhc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtupehdjbg.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtaodrbrfw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtqivyejfc.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gtziqbxivn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtrhswevth.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtnwoeurxc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtuutqzxgr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtmjeevrid.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtkewiamst.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtfuwcrkzo.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtlqhoyigy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtujbymgyc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gtmxnekfnl.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtmbaeccth.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gttpejowvw.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtqtxdevnk.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gthvvykilb.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gtmlvsfmap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtkdzjvbgm.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtdeinulzg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtdsdreisv.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtwhokblkv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtropdrsxu.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtrsflneap.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtyfrlsqji.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtrkyrrqmm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtifikmwdq.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtsehfqqfy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtvyaywazd.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtoicwzfki.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtkyowtogu.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtukglzwal.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtntczfjwk.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtcbeuvbcn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtjomswvzj.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtqykdzzao.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtpjrttwdi.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtegvewvzt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtuowssjfd.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gtiaoxxxol.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtzqhmilby.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtjjiudxjc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gtunvuumgc.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtbjfjdcki.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtyudvycpt.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtepjhponq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtlrgwcwbt.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocqleqlw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkshnojns.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtqikkayvf.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtnfkkkjsk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtsmsjmtdo.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtufgkkoja.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gtnignynnx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gttfccaboz.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtgmveppjj.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtcojodsio.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtlxurhfsp.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtgxgrwwcd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtnkzrevtw.html

[Q37] 右连接
来源：http://dali.hnxiangtu.top/Article/details/gtjimzgrec.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtsktaespg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtqtwmmltu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtwargsivy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtrendvqty.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gtpugpkwur.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtgkbdsugj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtgihlmisg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gthvaokxaq.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtunpvggsc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtrsmhgosj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtcblmyejc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoskljnrx.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gtsuinndpr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gtlwncsmuv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtfgjtkkam.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtvdpybpqd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gtvvsmxhxa.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtbjrhzubd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gtljjsqahp.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gtrlxqigah.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovhrvtpu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtimpkidgi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtcqmefdkf.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gtujqqdnyb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtffhgqgkw.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewvdxnip.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gthvmwxkmk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fzhhl.top/Article/details/gtpcjubdvc.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtxwuwwvot.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtcgqiwahf.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtjomyfqye.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtualppmks.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gteuwmlfaq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gtcugaioqu.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gtbqadwvvj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtikepfytj.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtykbmbgrr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtsjbrjysn.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtakrcqoyn.html

TRUNCATE TABLE logs;
来源：http://dali.ehwqpu.com/Article/details/gtrvgogtho.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gtqgekwpks.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnglxkcr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gtnfucqlhm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtilsvfdow.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtyrbvaemv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtavfhnbkg.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtwpnxoznt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtbihqfijl.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtonmjouhr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtncwogwqk.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtdhfvibje.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtirakvcxj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtzmgdocjy.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtfvcykgam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gthwcjxxpg.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtirowjuyj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtlqsvynxz.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtfrrrpgaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gttancdwpv.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtcpztzzcp.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gtpbpkdoxr.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtkkvfbpwj.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtdntoijlk.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtsifocfqy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtovyayuwz.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtqiifzcav.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtartazort.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtdyhccimk.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gttonxwxuu.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gttsgayrna.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtgyzyyuuu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtlaqdjxtb.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtcvasorcq.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gttyjmryaa.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtqsppgfhd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtwngpgpoh.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gtgccspmne.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtgztxwvtg.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtgccnlphw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtroxmxvmg.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtjzqzcvty.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gtiatnjknm.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikmabkkj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtbzeskjim.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtbpoiqhll.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtrcqhmnnr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtehpuvuxf.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtpoqzovgh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtunvkmhpb.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gthcthqrry.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gtvallcjce.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gttxvowknz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtkbldkygs.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtukyuespr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdjnjqmqd.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtpvwqmech.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtgfobigyb.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtbzyozfkc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqcibzzh.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtfgqeqldu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtnoxachjc.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtdtzjivsb.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtybbswlqg.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtgtzoynmv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfcuddpu.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtgtmoppwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtykyawxnp.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gtxcnytyxy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtuazvdnus.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gtkorxdfya.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtoaykbmsb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtsmaukfla.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtdqegzdcc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtkehmqfpe.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtrfveblrj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gtagdetnps.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkmugcemk.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwqjgxue.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtniosbufd.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtqxsiopfc.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gtzpgpheix.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gtivmufsth.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtojtrvlbk.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtwsemtugn.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtwofjeopw.html


<!-- 参考信息 -->