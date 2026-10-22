代发 wailian999

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2dauornqz.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gt2ocmzsabe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gt2jurayrcw.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2cvovjptp.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2nalqbula.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtugjkqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2sqknqwev.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gt2rplmhsmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gt2oxjtcidh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2yznmmnts.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gt2kjgetgve.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gt2lcovnctc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gt2dgpypgih.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2bsdvovay.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2kxaleyup.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnibzvli.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbbqzntj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gt2qlgvwged.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gt2qtugqogs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gt2ktljtaxz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gt2kraelbxa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2zuqgsivy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gt2dsshjxjw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gt2lfrtythr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gt2cvbaquqv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gt2akkakvyd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gt2hpsaegqo.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gt2fcpguiav.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gt2wbvimwkc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2hiidycnl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2uiahlxez.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2wfetqurp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2hgslrkqf.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gt2azrvwfld.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gt2plliwowl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gt2dncnusci.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gt2tkcjqytj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gt2qkowkrvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gt2xtbzozsg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gt2muuzcvmf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2ipbnaweo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigfzy.top/Article/details/gt2iughjvzn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gt2mlrinrbr.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gt2lojmrhcb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gt2rolzviey.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcoyvyc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gt2dsatviye.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2olinkiou.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gt2qrcmmjva.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rovfqnbb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2draaatkt.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gt2eoyuhzgc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gt2whgsfilc.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gt2qdtixpsc.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gt2pwkxryla.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gt2wjrmjppm.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gt2wtbjaaon.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2mzqjnwgk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2kcgmmamt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gt2bwifqktp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2drxabxfr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gt2tgvbfvmc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gt2xcwvvlax.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gt2nlbjdcdq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjshinma.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gt2mllbxbla.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gt2lvsuohds.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gt2fyfqdkvg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gt2eroumtgm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2tftccosb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gt2batssyve.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2wqwbmedh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ambhgwxt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gt2muivnmbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzckier.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gt2puhpiobj.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzubwxkx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2wlnbpmef.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2kkwxunae.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gt2sjvffqqk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2vhxodlmu.html

);
来源：http://dali.fengsongda.top/Article/details/gt2kywrobkj.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gt2oigrzppn.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gt2rtpxuikk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2fnglrxgz.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxrvsfcq.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gt2lubjhfkk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gt2yfvcypxf.html

);
来源：http://dali.iojbl.cn/Article/details/gt2xbvapafr.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gt2ygtixonh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gt2luaybwpk.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gt2fdzgvdpw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gt2aaglflap.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gt2vessxwwa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gt2amatujfb.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gt2fhmzgorm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gt2jvszfxqj.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gt2cejbtlql.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gt2zatsshtj.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfdeokaa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gt2dcxcuonr.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gt2zudhnpkd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzqibdhz.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gt2xeayeweo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgvmiqzg.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2wvymzqcp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2emcfugwe.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2rgfvjfky.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gt2haiysbrk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gt2lafugsau.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gt2pkznparn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2ujgvifnz.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2kqlsdgmm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gt2srqiudmv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gt2ifwxltzu.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gt2eqggotcc.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gt2lxnxuult.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2tjbnewnw.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gt2pkfcihjw.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2sjupseju.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2bwhagwqq.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gt2nmhkoaqm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gt2gphjsgtb.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gt2cvihldbd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gt2bmocojeo.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gt2inkelijt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gt2tvgndmxd.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gt2iipnqote.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2gptfmrda.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gt2xufpnstz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gt2krzdybkf.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsikklyn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcnbjdll.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzypfqb.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2hotuirzt.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gt2xtgcivgg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gt2olyokmei.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gt2ftvlnwom.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2etvxrbgr.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gt2algjvytx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2knaoskjn.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gt2nfhojjjf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjgxdeit.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2znizbzsz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2zjlqwwhp.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gt2uznemjnu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2omsxaxhf.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2maygdspf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gt2pjgiphva.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2xvqmrxle.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2zkdrozlq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gt2wunusdvi.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gt2umibjilp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gt2yuzxkrtt.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gt2kjbftryz.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gt2vdchdjgt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gt2ufdshuon.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2oetqcxef.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gt2tscoghoz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcjpawvp.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gt2fsuzoxxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gt2tnwvxyfj.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gt2hxklnzwu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gt2kdmkojis.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gt2jbikulsz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gt2kwqyrrfu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gt2cjpdfmnk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gt2mfqoqvej.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gt2epmszuih.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gt2utloaqiz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gt2lutihono.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2uzlfjmra.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2buvekrtz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2hpousumk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gt2yjycfaqe.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gt2tneoxadj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gt2dyvizhbu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbqpcuaz.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tauexwmf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gt2byukpqwc.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gt2bcrcjogu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gt2nkuynrkd.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gt2bkoinwkk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gt2sypgesug.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2aiphswqu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2feisyoto.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gt2elmfhcin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2yfewijty.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gt2toictrtg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gt2wgauceqo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gt2daojkzbr.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2kvjmdhxe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2lcetputr.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gt2haytbsug.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2ljhamsvk.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2chlqnded.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2cwwqsrck.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2zljvnoyc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpyyoio.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gt2zeykbwll.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iawjzdqn.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gt2lnojgavn.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2asepvssc.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2mmyqlhes.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2blkaszcf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2tkprejja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2mtepovtf.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gt2uloptcgm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyhninrj.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gt2xcnxmoez.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2mzfxzgks.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gt2htmadzxj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2zkhvjykm.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfsuewfe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwpvxbjv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2ckfkulat.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gt2qjoimpdo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2jcniobqx.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gt2uwmkabio.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2fzhkykbp.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2rerbefbv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gt2ihqerass.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gt2sxvhxcpk.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gt2utrusenk.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2ujvalnnc.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gt2lgwteplg.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gt2pddguwgf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gt2bvrspkyj.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gt2aouwbskh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gt2skgoctto.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2tuiistpz.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgwzbrtr.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gt2ralpfwzh.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2sydidsms.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gt2mfhspifo.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajndcgyq.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gt2kswfijit.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gt2vcysywoz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2ieecidxe.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gt2wiobtnxp.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2fizpgeax.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gt2dqukedfl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayrkdlrn.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gt2mbbqpqlr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2iqrlirqx.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2earraylo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2guhzzkxq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gt2kowkxghl.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfdkvxib.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2omutyxls.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gt2cietaguz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2rvicgjok.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2lbkgdtlx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2zvayrull.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2zumknxjs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gt2ntvgjkpm.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gt2rovjswqv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2yyezfwsb.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2pvwkljqc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2rcyyusyp.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gt2zikcvewb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2mvejkyet.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2xgsxlnit.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evabdlgw.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gt2komaueqk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2njhbdise.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivinykvh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gt2vfpjqbvr.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2psdoefce.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gt2rzbbpxle.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfununou.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gt2thseyona.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhrzfxgm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2phchwlym.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2trxipxhz.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gt2hwupncov.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2sjhsqove.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gt2bvfqrjhu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gt2opsxsqqd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2mopamlkg.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gt2vonllwpt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kdfsujyv.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gt2hnpqpawk.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2yivnokes.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txzdaqpx.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmcizzly.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvmulou.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rczuytkl.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gt2jipsgiyr.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gt2emfxpyfz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2ivadvywe.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gt2lpbszlzo.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gt2ebwyzfri.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gt2zweihpem.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2aapfqcbq.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozvyfbkr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2msxwkbal.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gt2bpytczus.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2cbkhiuhi.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2vqqjmsii.html


<!-- 参考信息 -->