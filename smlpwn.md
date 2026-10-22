代发 wailian999

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtucfwykpg.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtavauurdr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtpqvwkhbm.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtagzerdbj.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtramtnnhn.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtqncunzoz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtgxwwyzup.html

Ruby: SecureRandom.uuid
来源：http://dali.chenlongwang.top/Article/details/gtsmhqudsu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gtrhyxbtzc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtzreovjae.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtokjargls.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtwquujrxo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtqwjhdvbu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gtrvrbbeji.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtftducqnm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtsndtdysv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gtidmhnkeu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtdofdpygt.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtkjsrcnku.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtfeoyxeip.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtnjfjpwpi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtpqudzgka.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtciaxeocl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtnwivjman.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtrftdkjqm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtpmoykikk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtucftauqc.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtdlcgepjx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtkehqgthy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtfmanjvsu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtqwfjyuqc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtnvemxfbt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gttqjwbatx.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtcwnhnwjn.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuklzqkga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtberwjhgk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtwqhjsuqe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtqxrbazhy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gtxcsipwia.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcdrwzqt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtwywosntn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtppgefxfj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gtthqweyov.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcsizkgd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtjnwcidiv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gtthmpuyzi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtjgwvlfjx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktsmetrq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtkujfmxhq.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtgoivbacm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwcfoludy.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtrctnoaus.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjakaxcbh.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtqzsczaox.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtwqicnpfh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtwmmqlwyx.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtqvvhdvuk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtkewhdcwa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtsqoihenf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gthbqdqfdl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtzfwfwgde.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtsjngxkna.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gtviuotofn.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gtonwuposz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtkabydqag.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gtrmeygdbz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtamionqub.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtgnnakodx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtgobnedtn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtienwsgfy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtscxpwaqw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtqrhuwkeb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjelwquje.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gtjcuymzwd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpowvopvn.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gttdupbqnp.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gtwoyrohdm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtajxlsbey.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtsevlmmjg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtjntadtsf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtkgsxhqdt.html

);
来源：http://dali.dashuyun.cn/Article/details/gtteduhfxj.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtiwfjtqht.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjxlgkvm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtmuybawhw.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtalraxmec.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtcbaptfva.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtrrdwumuo.html

);
来源：http://dali.xziqi.cn/Article/details/gtfmdihpyi.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtquejiuxr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtdjyewdbl.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtryafxgcl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtkdbgihtw.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtgynukayy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gtjemrzwfe.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtscptkoyf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gtuxedstad.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtkvdqlzfj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtdjtmufdc.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtigzzwahm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtidbyfgqx.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtxqxmmhtv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtgtmtanoc.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gtiaylhgfu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtujljbdae.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtrplzduel.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtqzmuolgw.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtbrzgifbc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtuafzqvgk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gttddrkrxm.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gtxtypscie.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtwxtnxzwq.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtwzgnjvjd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gtweqhdaky.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtwxbggbzk.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtqebxzaym.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtjovyprsx.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gtlkjkidav.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqveydjfr.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gtzanbhhzu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtdlkodxmc.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtrqvjimuc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtqbkvcbuv.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtofwgmfud.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtrbmxowpd.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtfbxocnog.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtrexcxusd.html

[Q21] 空值判断
来源：http://dali.jyoumei.cn/Article/details/gtpwlafmml.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtrsrkdqyv.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndcxqkbf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtfauycgrv.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjqzzkkf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtvztsmkju.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtaeyqltyo.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtmpwulrmx.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtiutmxlql.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtarloqior.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtescxmjmc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiomoassf.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtbkolawpn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtsxpimmza.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtwywhcjhn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtjoszbuwu.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtoagerkxm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtwvgroteq.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gtzzvyzxxx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtrhkvfzrb.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtbemsbpzs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtydqiqnks.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtoxlvvrnq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtemfodkpi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtivpzjkab.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gtzlfrhojf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtjrffudar.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtmbznpccw.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtxklnswmz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtqivscybe.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtwuyzvhkp.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtjtzjncnb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtbklwytap.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtcymfvpfa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtfbinrwbt.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtimkxmfrh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtngjicjld.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gtikhnouiw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtgtbgjoov.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtvyrwbjqm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtxfxydsuu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtfuretmfw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtusoehbvd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gtdpfqmsew.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtioyyxpjd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtcwlqvqgk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtzudsbkwe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtkpgxccqa.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtldlgnyeb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtgbijvjiy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gttwtmhocv.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtiwlxalgt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtuibeykli.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtsmolirdg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtedqeundq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtjodvickf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gttnpxkfgs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtinwcbzvk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtvymdycjg.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtvxczfexy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtxschvwcy.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gtgwvvldgs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtffgcmjds.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtfdpjgebp.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtznlcwmsk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtupmqlqnu.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtningqhig.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtuxhibnub.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtjigemzsx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtqsdncblr.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtzqsoqpgx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtyfdsopdm.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtdlyqyotj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtnomnadds.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtxrxhtdfi.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtcikzxfbm.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gtihukejqw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtpzhyxxqj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtbhjctqwx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtwahkkzfs.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtmipkhpfh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtbglgjdja.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtxrlnajem.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtwzcvxuul.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtacqsrriv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtqkgmfntr.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtmskqcmxb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtqtwhuort.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtsqjiamss.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtudgvlvqn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtilrtvoah.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtgqnndgfd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtrottafxs.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtiwkwpuya.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtyxshuvpy.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtusqjjiyc.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtzpjebthc.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gtimeonshb.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtpkgiuwpb.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtptbmohai.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtzlhyzank.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtjirifvln.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtcdjpjskn.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtarzwieit.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtndzoyoma.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gtqnjbuvyo.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtsvogpmgb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtvvrdpcar.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdknkfah.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtokhveogr.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtpjpxxdch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtrobrweco.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtuimheryl.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtgmoiudpg.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gtcnriccmw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtnptqmgdt.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gtlnletree.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexoibfbw.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtefzkomqh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtqjsysvpr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtfiitcqtf.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtkbsqslxb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gttkxiunih.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtjzoomarb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtnlszllip.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtuxrmebcj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gthvreihry.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtusrsrypa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtnzaupbmx.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gtfweupfsb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcoqcvztl.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtizorejkt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtwswtnipc.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrmikpqj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtjkytnhry.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtwdqjsyyb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtybygtugo.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gtopnfoxel.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumwufnkp.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtsulybphz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtkscfmkbz.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gthfdpnscp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtxsmcljkp.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gtaqstwkye.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gthgnjqvic.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqlbsoqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtagdramcn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtebgddpfl.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtqbauuign.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtjrcfpcdz.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtkijgpvqy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtfmzdljgn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwlsrvnsg.html

R. Bash 专题
来源：http://dali.jianghu66.top/Article/details/gtabtcvmbg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfghsajyv.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtpugdmxdt.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtzfcqfbjc.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gttgzqomma.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtclkbgbne.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipvhnqzs.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gtzwupcauo.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtivvspopp.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtotlefvyg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtrbbhisld.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtbdjqkodb.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtbngqaowf.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtthtyodcf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtdsbircky.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtnftpixjk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtjrcarxqy.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gthpqoopnf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtcyehzvns.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtlelimrim.html


<!-- 参考信息 -->