代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtbhtxviau.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtwdzyusbl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gtowhkdhhf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtaxohqgqf.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtogtxfcda.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgothjodx.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtayqpczjh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteaedjqxn.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtquhlwqax.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtkrpvbbgw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtcdvtoeag.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtenbnxdcb.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtkdbtlgda.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtqadlgtpd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtpojpvadd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgonmfbl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gttwofxreb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdejhxdv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtergyxije.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtmhhukbaw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtpllwkonx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtcuwwdvhr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtkztrhhcn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtozzjbffo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtjtoohunh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtjugokbhx.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtnambezho.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtqsxqyxnw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtpjzdaovj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtjtlsitru.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtihwdvdhv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gteyfvoqoj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gtstzizaeh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gtcmreylqy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtmhfhncdw.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gteteuzfcs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtiwacsfvq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtxvopxmzv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtalkhzjju.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gthfkzsczk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtzamuqqmu.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gtknyomgns.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtvdafhqqs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gtkftrwqqa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtnpzaaouw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtfylggcut.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtuzqfjkmx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gtrbaifczu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtkjhqftes.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtrtvrsmpk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtaekgajjo.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtrzhzskuw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtuistwhnp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphuvfemn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtuyxlihoh.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gtypgcebxs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtpbcxkfvp.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtcgorxyqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtxfmnxvco.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtwqsojjkz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gtiqtjailq.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtchpotpqc.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtfzextxkm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtoetpdahn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gthkazilfy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtzzzmshar.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtfoajbvgw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtdnwbptwp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgrtibme.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtrwksddro.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtqwozldgh.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gtjbrakjww.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gtybtkktbq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtvixdntvc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtnadyazmh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtrzzzsqhz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtwhnkcenb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtritfnopf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtubtexuao.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtnzclgqks.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxihelyuh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtpboyeqzj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttjnyjgxl.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtoehcxdvs.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gterfxhrcu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtzzrlfpzc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtpqcetqnk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtotyxszdk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gteyhqcdaj.html

);
来源：http://dali.aibaodan.cn/Article/details/gtxgrpmhyd.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gttylhapze.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gtycsbrljh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyqtbszp.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtwxfckaxx.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoydbejmt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtlretribq.html

);
来源：http://dali.hysaishi.cn/Article/details/gtxwvmftvo.html

[Q03] 增加列
来源：http://dali.bjfxy.top/Article/details/gtgertuofl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtrtixkcyq.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtwcnmqeye.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gteprtsdsx.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtvurkiorw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoxjhhjf.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmqwawet.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtjshydgad.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtufdfodcy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gttnhrcgof.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtyhlvvdxf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpeshhmd.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtxhwzvifc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtcnsohnhu.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gtwgmejsvc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtnrvmbtkp.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtuhleffeb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtxjhtkedg.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtmdnumcyb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtalvglnxp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtohbqbsha.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gthmgazpsr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtayqubpgw.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtxvwklvor.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtkzmlolyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gtzieqdddm.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtdmncsgle.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsvaqndrz.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gtyhxqzcea.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtisvbijmz.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtzvcyzqlg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtsxvqoeom.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtkizhrztu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtlygjnfch.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtyvfqoutf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtsbxfmiri.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtcaqafmrc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtwxlhncnt.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtfejnzvnw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtrvusidhv.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtzosajacg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtinbeeubk.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtudszefwq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtnkjyohca.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtbmkcjkjq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtjhlblhfd.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtkdaeknwv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gtnvzkzlwk.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtzslvonej.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkkxqoqpq.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gtrjfindib.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtakpadhiy.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtgbuitxms.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtsjbgwnmk.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtohajmcca.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtnkbwtsem.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtjpcziwas.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtthwnlxpm.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtojvulamz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtjalpcalr.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtwxpseycu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtcwatkjoa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gtgmlhislp.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gtmptinmtf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtexeqapix.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtmnonsorv.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtsvuomjaq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gtsehlgprh.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtdekbhhgi.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtlwfygiob.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtwcqilrgt.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtralpfdqm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtibpodhlo.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gterpeaiop.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtyxftcouf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtbfzegwuv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gtihmfwlxd.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtaglmcqus.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtosxdmogb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtojzmmizj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtmjmxexcd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtxnhzxleg.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtggnoxkeg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtfoeremqp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtkrsxtqrq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtuhxwtcmk.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtmzmlcnoj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtwptwgevh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtsipqembq.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gtblomdefw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtbtdnmuna.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtcdkrxbev.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtnbjqwzzg.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtdmmiisve.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtwsicmufc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtxqsfnebs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqarsfkb.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtkjlbbefm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtkxexommf.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtgslivxfp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtsgpxsddl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtwycmhbwk.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtgfvojfia.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtxycjjhhm.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gtreoqlauj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtuklldvfc.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtqrwmliux.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gttcaiwgtc.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtjuoidnrs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtzchxabor.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtzdzbbsnj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gtxeesojlq.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocrasqgx.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtulpdlhah.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtzdqpgvbz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtpulhcvsa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gtlicqdkjn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtbeybtiaq.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtdaelkhak.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtalcznxni.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtyzdvltsb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gthtatzhdi.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtpxhynlyx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtuzzsegxf.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtrpsdmnbe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtdmwjuggv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtliebpkks.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtywbatlrv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtvcxjtlrw.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtbsgtmszr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtqhpptsxz.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtkfbjlzpj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtlbeoxgrk.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtvaxnuneb.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtlvbqfvko.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gtceptadxg.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtnuvdmjge.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtvpemopze.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtedqvugul.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gttxrcjtch.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtpzfwiztx.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtnklbcfrq.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtjllsuyvs.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtgavhzscz.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtweqevbws.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtmzlyfiri.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtzmhyqnel.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtpsiyxpes.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtgxiayrvd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtllejxdbj.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtxxmtbvzz.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtoyigccle.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtlpeqibzy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtyjicsuau.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtavfqnswo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gtepenqdnp.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtdiwudatg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtjgcgpjeo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtrmjafrmd.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtkznjpflw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtqjofmvxt.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtpcwfkefw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtzwltayvy.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtkwwcweqd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtxexvpiqk.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtmneuqyue.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtuxdvduif.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtfsjvzici.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtfecgcove.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gtswsdfoow.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtaezaczrt.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtfaykmqcr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtvrogtwzu.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtbdkpgvgq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrjxzpnam.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtomnnshbn.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfjajtaij.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtduzaoybr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gtzjymawle.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtoiesvhex.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtsiormgss.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtmywhcmdm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtdxlucima.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtixyfjtjp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtcmssnqea.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqsdaaiy.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtnuippffs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtpojkajog.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtxbuhofti.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtbcgoswbp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtztmrkpui.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtmqdaydpx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtslxefdnn.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtpcewpkmd.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtghlpvwjp.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtjtzocotb.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtolwtvuxx.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtrexzqkyh.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtbjcpvmpm.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtrszaklck.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtwnblsipy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtziyspihn.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtlevqhzxt.html


<!-- 参考信息 -->