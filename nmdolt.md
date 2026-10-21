代发 wailian999

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtkxbecdgy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtulhzerkt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtsmbtivkf.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtyasbnwqj.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtggrtbhab.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtfexstnxb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gtampwkwql.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqypshokr.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gteowblauq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgkmzxaba.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffrdjgjk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtoketaoxb.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtkbgxqbud.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtszaxtgxf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtqwfqxmqb.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtqdieixow.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtnkveydbx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtrtcgpbba.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtgpinnacm.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gtmbrjlcfe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtiwzvdgds.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtllebhmyr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtqhshqznt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtnzulawrp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtizhotbzz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtdjcmmbzu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyhiislx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gttecetkil.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cdnleiting.top/Article/details/gtagmurxhl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtzvqphkvp.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtbgivzgbe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtepdbocqh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtaiftrgpe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwduxzwk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtnjpqkuat.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtnsvupftp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtlivztbfd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtmukiugjc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gtkraemnkb.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gtqfujjijr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtobasgybf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtsmhkzpzc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtpodvisoh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gturefwzvd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gtjmwctgax.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gtgiuiwhdw.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtlwqgkmco.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtskchnymp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtgtpmogoz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtsdogtuyb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gthwrwpqig.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtrnnyjaoq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtorkxqcmk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtvilafpyk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtvfsgpndw.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtihtbdknf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtohgfdxzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtxivqbnox.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtkzzpwdoe.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtighhgsyq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtyourqnmz.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gttghxscnj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtqmbsilrt.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gttpgoxucu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtlpafivzh.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gtqpprtlsh.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gthutrdomz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtloaftukn.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gthmidyhdj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtjqpyimuk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtkmwinzty.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtgswdtpht.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtpvgyhnlv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtdseaoewa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gtzofeottp.html

[P08] 处理浮点精度问题
来源：http://dali.xuanzx.com/Article/details/gtcpqzjnit.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtzpleynao.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtuivuanxl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtglsnvjlv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtglrueujw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gtzxugiugb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtsqadrmiu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtyamnbrfn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtjerfagdb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwjxvmazu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtpgdjcnfr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgxcsgoug.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gteskpfcfw.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtwdhbajlj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtlduhqrzj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtmtbdjvkg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtyuwfvkwt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gtanailzjv.html

);
来源：http://dali.ivvv.top/Article/details/gtmbvfxgym.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gtdmzcvdyl.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbpaucmy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtukqgxgfq.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbmzpxbq.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtefbhdmme.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtmnoygdmj.html

);
来源：http://dali.tianlin.xyz/Article/details/gthguuvwge.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gtpwjwvjuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gtkaraisst.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gtjfktobhw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtrwazxtsd.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtabecaxxp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtfzqijgwa.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtsrjabnhy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtrwxmwiyn.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gteijcrjtv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtrqsrjuvb.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtqhqkcgkf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtrxjeilhi.html

[Q09] 创建唯一索引
来源：http://dali.jlsjyb.cn/Article/details/gtwubiqruk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtopfbxmpo.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtwmnuofog.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtuylmazhj.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtspfxfhtq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtjpydmxoh.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtigqgcdnw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtvmsbuejq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gtiaamjvau.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolmbgfnd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtntcysipj.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtgjxxqray.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtwvjigpcz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtiduerxbd.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gtqpdmwlmo.html

SELECT * FROM users;
来源：http://dali.bjfxy.top/Article/details/gtosbtncdo.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gthafqanmq.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtjwdsfpgk.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuylwsvd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtdwqpgmpz.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtbacfqimt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gtvsndhrrj.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtcgqtndsz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtvapocpzu.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtqyxdhocv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtywjiixku.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtyhcdevko.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtelcwkgkl.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gtptvjtsqk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtvjyvizqw.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtqmmolzit.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtyfqydnvw.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtlnfdwnht.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtqjngktrh.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtnpilxbhh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtiwqsykkn.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gtoseeawsv.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtotayqxim.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gttxcmszze.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtsuoymnkm.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gttppkckkr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtczocvrcp.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtvowsokrk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtftwyalng.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtnlzotsxm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtgtpdfoxb.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtagihmydl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gthlkwdlbn.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtvwtaamnz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gttowftsyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gtuxlglriq.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gtzkjinzar.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gtovgojvda.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtxyjjqphj.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvchntqp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtvpeklgpw.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtdtqbciok.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtvnhlwmcy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtxkxqewtk.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtnxkeadfk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtyafdpozg.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtubpwlhtt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtivvapvqq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtnfbkpdyv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gttdrvevgm.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtsuwyhpzd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtjwqtrzya.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtfpgpzgdp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtosrsdhvp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gtpnpsfbyt.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtlvdvgdwk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtkznvbzoy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtqgqxbrcw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtwayixxdc.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtvjctadel.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtegmkebru.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtkukexdqo.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtividjkfc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtyjomjnxq.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gtwimlfujj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtvzjmptsd.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtqjfroivx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtcppazfnf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gthagkhxiv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtapgpvase.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtqhyhajti.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gttfxwnmoe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gtyxaoxvsg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtujuvogtt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtqejnrjna.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtmickpoeo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtdqlihcpu.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtaplbahtj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtvrlwglka.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gtkvxeaovv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtfxcsnvev.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtrynvtqhg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtycxdjawq.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gturkfmacp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxvjftkn.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtmhnuayll.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtleeeouep.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtmoxldlnx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtdsoludoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gthxxyfpvu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtnhxvwjeo.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gtmcfzqkrg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gthomqkppm.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtsuujuyoy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtkhknufwx.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtoqcljgkr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtjrxqxbjq.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gtaohigxgi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gtjwctevxp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtomlmnkwk.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gtxifjlmij.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtkmxvyemd.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtncfprjfq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtviaxhkpa.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtaurtftob.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtjlqpgooe.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtybrfgztp.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtspnvpnhx.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtzolzlmkt.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtwogfvxfc.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtssrcxuik.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtftgkaxkp.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtabtldopk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtatthcjpm.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtwyhjwvou.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtrdvlzrjl.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtvwzlpspl.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gtpnaabkni.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtbwwigmig.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtjxmknvmb.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtvwzocalk.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtqdztpktv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtwxuicijw.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gtrrsgoput.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtxnmudowr.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtqgwlpixg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtvvnelqmb.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gttcqomzks.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtdufilnws.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtubvamjsy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtkjgrzxpv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gtmfhiqygq.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtcmvxzrqy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gtrkwjexor.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtfejslpjr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtxccpnsua.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtzajecove.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gtyqiwgzou.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtjxbmxpfn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtaeghacxf.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtigjciegj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtficohszj.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtlxksoiig.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtenetiwxx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtejlcupmy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtisrnltrs.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtbtumhhyl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtddwhrfqw.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gthwdlrhgw.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfatxhvfv.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtnbbpnqws.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gtupxtoqih.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtnspcffpz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtqwllxzga.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwumagod.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gtosxceinm.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtwfvjyopr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtwaotrmhb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtsdfzwkfa.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtjpbemglr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtzuvpjnkg.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gtdgfyxufe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtklrdptkn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlpledwcu.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtjkccrywc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbaujowuw.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gttsgmvgyj.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtqkhdutoh.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtdlciimwv.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gteqnbandu.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtjiqphxth.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtsssxxtzv.html


<!-- 参考信息 -->