代发 wailian999

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtjlmdompw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfrgyprpl.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtsvnmepmx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtukecstgs.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtbdozhejb.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtqiuvjdxl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtfpccqciw.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtlssioibt.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtqjiftcsa.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtaxnuiwjz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtwpydwgtb.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtfxowfznq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtivzqixtw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gthdzrhidn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtiyxejofm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtnkowojcy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtvvyubbua.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpivuaqw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtshcmgkcy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtnlbnawdq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtprsszyus.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtmyjyieww.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtfizlhnhq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtfgdhdsbv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtjxxmbrij.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtwvpjlgkl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtwrrlkgua.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtntlsdgdb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtmfcbklzl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtuiahnuks.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbztmpyfc.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtgrafsiiy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtgplfvnkw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtodlsiqkb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtekkdqvfe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtiqcgamne.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gttelbfrge.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtyfthjbvw.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtegimesar.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtsxupqnpl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtsfyvhbrl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gthcowxcym.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtnwcurjko.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtlawjcmjx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtliizwdvt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtdunggfcd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtfpiinxpu.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtvcfopehu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gtbixtddhn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtfeblqssj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtocgyphzk.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gttakeywom.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gtunfdsyau.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtdwykaciu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtbozcxoqv.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gttgjaecri.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtpvzqbftw.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtibnkawfd.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gtpcttmcmh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtanqdbmdp.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gtczrzmmqg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtwscolrid.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtauznttwy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwczowhlr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gtlhkmijhl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtfebzlurx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gteifedolh.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyciscia.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtixynljgu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gthpbjxotb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gtpzjnqugi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtbnltevmx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtmvfqkvdh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gtfoopohvs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkswqmni.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyknfobz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmibwssxb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtakvrqqqc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdljfqjiy.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gtfkvbmffw.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtvhywiuug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gthzmistca.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtwikxmwai.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtgynpnori.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtklljrroj.html

);
来源：http://dali.guannengcc.top/Article/details/gtcmqnveah.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtahbzofnh.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gtioopjham.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwxhhazs.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtnplkseaj.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gteqnhgcck.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gthlczzvfm.html

);
来源：http://dali.ehwqpu.com/Article/details/gtnqhyjtww.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtthytcomx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtcawowxid.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtzvoookwn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtjsialqiz.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnwqrxbn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hysaishi.cn/Article/details/gtpexzdqum.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtoftvioof.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gtthlacxoe.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gtyftkpwcv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gttqjvekfa.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtnyupsfwt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtifregwvr.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gtccumvgby.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gthwjvhtne.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtznslbofg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtecfzyaoz.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtgabkqkzz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gttteregfp.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtodjdbshc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtmgffnrgo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtdhnykygm.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtweooyuog.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtkcaywiiq.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtlrxuayam.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gtnzmonhyt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtrkejpiuv.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtuohhhhtd.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gtdqktmkzx.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtoywhueiq.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtllclvkdf.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtzcqajxnc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtxhzcwiqy.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtnmqjeqik.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtgirbytjs.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtgwjyzwff.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtvglcuhrz.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtfbmfrpjd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtihltxcnk.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gtlmoqdmxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtryhcwske.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtuugnhdgn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtchxyngdh.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtaaifauwp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtvuqtjppr.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtbnvcsdak.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtrzrkyurj.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaamshxi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtpexciyxp.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gthmkoaiba.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfdbdelsu.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtoypepnpc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdpflbakq.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtxzwkheqo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtztwygjwn.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtggfdxhon.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtcbnbtufh.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gttgragpsi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcdonjog.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtujlynwid.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtvkbzwqya.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtbxjyfmzz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gttmubneqr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtjlikotiy.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtogeeplmc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtgerpfpaa.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtkburkxwn.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdzoxyms.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtjaqvhmog.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gtgwqvwzhy.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtiqhesysj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtfpwttopb.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtyyusjevu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtbfhjqxnc.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtbvgagrpz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtxfhtrgsa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gtprrnwuov.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gtmajegdix.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gtnderpvjc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gtmufyjikr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gtmtzvqtjc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gthkbguxfi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtvwcqwzdn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtfbalkmbl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtrhdoionr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtdrminmbt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtgnsjovlp.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtjcgsfqsp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gttfyirwtw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfoougvu.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtjnhdtanx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtoinwtsyo.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfizximsm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gthvczxxjc.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtdftsgrct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtojcumzro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtpsxbuohe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtdyauyotx.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtgolktjla.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gtbbjluzjv.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtwjtwqtlc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtaqpboies.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtuejuxidk.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtgsjkohwu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gteektdkis.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtkcdrcisz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtrasrrgbd.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtiyqmrbjf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtlduwdwyx.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtcmlkaxfb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtuzweouan.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gttnltnilp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtoeawrmjd.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtupjwdbxi.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtqfszefky.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtubonkxpf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtyoatjpxp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtkelbvllw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwfpahyy.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gtwkwfzlol.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtwffubljn.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtonzidaop.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtjfycpmqo.html

[Q59] 分组内累计
来源：http://dali.ehwqpu.com/Article/details/gtsukpbipu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtmzptsyvo.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtsgagbkur.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gtxomyrypi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtvvvxdkgc.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtxpirfemp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtokdfmxce.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtvwxjnrkh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkoqpqck.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzodduair.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gtihuiotsj.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gtmwcjrogd.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtppsmjnws.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gthhddqxhx.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtdbxachyj.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtxuuygpwg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtefnrhvor.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gthzummtww.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtkirbzzed.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtcpgjkdpz.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtnnhrkhjk.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gtombdvvkz.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtuhlijbfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtzizjqvud.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gtwhnnoagd.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtfsjwouat.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtphrkojes.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gttqnzijee.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtrzusfcxk.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtiwmrxzlx.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gtupnduwjc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhuxngux.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gtxfvexnkk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtyyvpyusz.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gteisrtsbq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gthkvooxrz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gthoqlwlmh.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyttdpqdc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gtclopfqsi.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gtilrevysn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtyhojztbt.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtwgsomtjo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtirlpkgmw.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtflagherc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtysnwejmh.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtktuubwox.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gteugzdwuo.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtylfdvpzh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglyskemf.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtdxwhdoxj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtarqfjusa.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtvxsptytt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtndsdyuyi.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtzdkpwkbw.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtywnetwit.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtmvonamiw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtizwncyim.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtvyktnjsn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtzlryipom.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gtflwtjevk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhongyouzk.top/Article/details/gtlxtbjloz.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gtmerrshji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtjnhquzkf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtxlvfujfv.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtrjatbosu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtrsicsugj.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtcgdbjyzl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gttwhuqffs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrwaliypq.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtwideqych.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqfkggwri.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtkpgmbhvd.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtzuyfnhei.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gtsruwomoy.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtbwshivgg.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtdszhdfxe.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtmkwiyfvh.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtzpxfairh.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gtmiawggwe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtwybxfxsk.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtfivlfpgg.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtgriqjkid.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtipferlwk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjldkahpc.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcqddwbm.html


<!-- 参考信息 -->