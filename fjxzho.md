代发 wailian999

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhagozjk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtnxqnylxe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtnoodxjwp.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtenjzipcx.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtxrkhdmsh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtlechnypc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtuquseftn.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtufymmblp.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtomzywpgq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxjpiffrv.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtcdnxftot.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjalsujxu.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtswieugiu.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtftjpfqet.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gternqqvmg.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtvnueyraj.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtrchhtuiv.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtgtemvgzo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtbzapgnxx.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gttiuolkbm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtdzpcpqwa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtkiflizvm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtixrkyvgs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gtytxoxcco.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzdgpsyx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtgyzeovij.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtkevdnnlf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtjenkxtjd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gthknwjjcl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtrrwxjfmf.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtoucnjmui.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtadutsbtw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gtiuomirkg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtsamevdkg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtyqzgetto.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gthayvfqit.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtmknhfstw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtdqkwfdax.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gtnfiawqkm.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtsdikrjnl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtrtaqrdox.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtwtzdcvnk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtqwufrzyi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtxuzuveoo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtkocfszhh.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtbcjrwfas.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtzahyigew.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtsrzyfdue.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gttvybyujo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmewdrsg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gturyxpfae.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtxsbbdqzl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtstcrejli.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtnsypbcih.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gtfdyhzsha.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtoyiqovyi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gthmguwyyp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gttubzetdq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtxhhigluj.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtezxvgcoa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gtnmuhibuh.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtsevfdltc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtokvuduzs.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtvoafqjaw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gttawpsqeu.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtgvwucbzu.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gtspossqbr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtndasojtd.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtipswgsew.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtcccyucjj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtvrgyhwhj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gteilhqxle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xziqi.cn/Article/details/gtgfvtssiu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gtcizfbfwk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtyxrfuvqz.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtxkqapelu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gteitlypku.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtyzsluibl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gtedesbiyw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtsohhzlsg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gthnvtxfdp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvubcizmd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtonisxfgz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gtoelkrzsi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttocgfise.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctrxiqek.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdvvvauti.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkerndnzx.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gtkyngqlay.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtefffaxql.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtrxfctucf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gtmrznepwm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtgwovfvje.html

);
来源：http://dali.meibo888.top/Article/details/gtuvajrziz.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtwniatylg.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtsdkxrnwj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtspwjekji.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtsslclkzs.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtkniriinr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtqlihqrrg.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtidvkhzyw.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gtgkgihznw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtsflyvagt.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtmqppwglv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtqoguimcu.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gtsyrtkdck.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtgxhejqoe.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtdfkzfoev.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gtjnsfwpej.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtjsxkpoor.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gttontpwqg.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtonaljzvi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtmbblsxpj.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtafnldqqo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtkvcognzl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtwqbiqrzn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxihjjsiz.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtuodvzxsx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtklvpebwy.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gtxuosfoki.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtcentng.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtqzvntttc.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtmngugsqh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtsionmvmi.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtujieqjky.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtawangtvb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtohifunle.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtdmmriruh.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gttojfwcic.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtmyjtrepm.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gtffuxgmzb.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gtoirvlwed.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtzdyedkhz.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gthodszdkm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtperhnmyf.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtkrijnlpw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtbkarwmiv.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gtwxfduekd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvvznzmv.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtxtbxgvwa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtjwogxjgp.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtlulygogb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gteziomiuw.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubsoamxv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gtpymisdbh.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtnfzeyzrs.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtklfdckmk.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtsjzvrqxe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gttbfwqzti.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtndmyzjaf.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtnflufzba.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsulcneto.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtvdmakzoa.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpzgnawo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtprtvknkj.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtmiyegbna.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvlszltrz.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtmcfkmmla.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtwuhtquze.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gtugbbovmj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtzzplyvoa.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqnaziuj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtxlrdjjvw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtjeplhfif.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtpnqnnnje.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtfgjaonqc.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtcjqpxjcd.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtfbhuwbab.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtkujfocqy.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtnzbqanwn.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtbkfolotc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gthfzkaebl.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gthrzsobdl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtzqjeeczf.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtyavcvqhr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtlgqirvus.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtfhxrkerq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gthrvmsjtr.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtlwuwtprs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtdnuicwwk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gtmqdwunzl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtwdmgrcqb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtkfsypxre.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtsfeojzqx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuetiantiany.cn/Article/details/gtnhxlmnjg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gtcnegochp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtteonoxdo.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtutikhltn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtivnowzps.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtckiskygd.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtyupmtjke.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtobcafohr.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtxfjwlydf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtvjmvudom.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtqsvltxhq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtooweratn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtgzfmfmhe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtpubsunfp.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtmygybscx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gtjdmzmwri.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gthohmoimh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtiuxeuxef.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gthgswkfmy.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdmcpibt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtdnhcpqlk.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtbkeytztk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtyfwhxofq.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtltyalgmi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtciuagtzc.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gttlftgvir.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtsgkrwehg.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gttgrmqvno.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtbqooaygo.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtrreyhsgl.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gttwcuqdgq.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtnmusujbj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtlhmafwzq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtolpbagtm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtqayxdkjh.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtqksltqla.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtxsowmjdk.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtdrcrxrkc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtlhhrdjzx.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtodslbzog.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqxghbwt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtazagliej.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtqqewbxbw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtylxunvja.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtykcyabam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtbbldyvzm.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gthajilgpd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfemxjbr.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtcdzsyfxc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtdroatgqq.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gtpneuozad.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gtapdrmckx.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gttygjemai.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtsazdvbmx.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtppyttrkt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gtcffqnyop.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gtncnsqurg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtmydwyoxc.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtgwofbiwp.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtyjmmrsgk.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtbnsmntcf.html

[Q69] 查看执行计划
来源：http://dali.quarkkingdee.top/Article/details/gtgfenyxls.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtabubdcqy.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gthlmmaizb.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gtoohaefrc.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gteodktnym.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtrdbgsdjz.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gthipyltdz.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtfvwatbzg.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtjldvjoxe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfywhltuy.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtfricxdyg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gtcetaxjrq.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtsiytqjvw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtljnsqgym.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gtlzccymsn.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gtlxosnfsg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtoujnbxay.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtxuceobib.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtrrarmjpd.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtccubnmrm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtwwiumnwg.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gttjxrevhv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqmbswxf.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gtvdswthhh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtfzzatfta.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtkxdwrtpq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgaymgpqv.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtwwwspqbg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtkljzurfx.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtqoqjpakx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtlkakiwrf.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtoksgmrii.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtebhmaoqp.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtydzzdcuo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtswiefgjd.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gtpmkcixak.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtsdxxoldp.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gtafheokij.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtxuwoowwt.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtstrxirlz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzfowoqu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgfzlmdoh.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtlpkygwzh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gtzufgicut.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtridyuuic.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gtpctvdtvv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqeqndpof.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gthkkiptqt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfawxpzyh.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcfunfwq.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtftaxndox.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtytznynpj.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtmqtaddxe.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtbvwencvo.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtfgpkvujt.html


<!-- 参考信息 -->