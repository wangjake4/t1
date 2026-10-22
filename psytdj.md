代发 wailian999

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2fscznzdt.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkjtpeuw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gt2xsvvgcqc.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2xyjilwcj.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2woozsuff.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gt2wippksqj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gt2teqaduey.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gt2mpqwdbbg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gt2ybmboqam.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gt2gasorwyo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gt2vgqcyacy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gt2bdiommet.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gt2pdedgnge.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gt2ncvavmzk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwzgfhqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpwjdozu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gt2qjjoxxjt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gt2zfgxsciv.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gt2dqgurnaa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gt2nhfzyrio.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gt2koeewwlm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2drikqqgl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2lcqtdhmx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gt2anzcsgba.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gt2rsgxrjhj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gt2eiytzjkr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gt2crueycwg.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unmggjxy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2lkdpthel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2vcvbkrrb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gt2vsgwnfyk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gt2pvuboose.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyfijbjh.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gt2bsmixzhg.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gt2hbialuha.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpceifxh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gt2cuvumupk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gt2hihythga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2btprqrxu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gt2caqvuhuv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gt2zrbzimxo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gt2kxdvpebh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2uomtuhwg.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gt2uwpsgdch.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gt2jyceygoe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muyijkuk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzckrjzz.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gt2ovjhfkwl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gt2fkedglyk.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gt2ivfwbdct.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ebbekkum.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gt2axpztlhj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gt2mklafjwu.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgmyrcim.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gt2redcbivo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2moxoucvd.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gt2zrzidhbd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2npcjkyts.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2cmapjudd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2glpqjski.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnzdknwa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2pdwkhyro.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gt2cqbsmrdz.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2slsbezna.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gt2zdjtpiyz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gt2cpbnfntv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gt2cijmwmvj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gt2aoyaiabv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gt2ilmrryxg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gt2agixdkpj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gt2dtfpkoqd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2bgfkydtr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2cbotnnfh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ievsjcwt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bbrtziqg.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gt2waxubnuz.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gt2iomlpyzm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2ztmzrtnl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pweceujj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gt2hgngvfry.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gt2tuuflrsb.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2aoblmros.html

[Q02] 创建带外键的表
来源：http://dali.zhoulong.xyz/Article/details/gt2issamcej.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gt2vukvweke.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gt2nrofekww.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2ccdjyllu.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gt2asybpzol.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gt2zpjytbex.html

);
来源：http://dali.ybcxt.top/Article/details/gt2ssdoawzo.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gt2kbfoyhly.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gt2qepcxkey.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gt2pxjegnic.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2xxkejlsm.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gt2rsoxsxey.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wseayafw.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gt2qgomrcsk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2bcdnwzrh.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gt2wwyeyppz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gt2whbwwxea.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gt2grviqmhx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2gxampzfs.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gt2qawqdcmc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gt2yauxtivf.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gt2ohmukzwm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2qbjcwbgq.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2qywstgop.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2jergnrab.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gt2fakuhgxi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gt2kbsjxrim.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gt2rjrhumfq.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2cwkgljtp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2uabefiyy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjfxluwk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gt2xprttuhm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdhdjrqa.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2oizuqarx.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2owyytpuv.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gt2lepbepsx.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ltrosbhc.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gt2ieyjvltj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuxbdxip.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2diqxljmb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gt2qrkymzqx.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gt2whjxlcgh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.smart0.xyz/Article/details/gt2yrxpzsgs.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gt2nsbvlpfu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2threqiez.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2tinrdshk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2cxcpnyqg.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gt2titunebu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2qbfrzfpd.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2bekfnqkj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gt2iztgxlvm.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2ghwzytax.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2brtliiir.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2vxxzcjkt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gt2bjhqnyhr.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gt2ornnjuty.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2hqkczyvc.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gt2hevtkpdr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2zfikbiug.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gt2wwbxncud.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2ffclbzkw.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gt2bdbjhorf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2cjvjhyfb.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gt2vxrhkmkm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2llqoavpk.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvnnkfvc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gt2hkbbzkgu.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2bgoosbad.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2sfrioani.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gt2dvbekewa.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gt2grrcqowd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gt2vxtiylep.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfhaynio.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gt2lzvycezt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gt2illztxha.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gt2ougqscdf.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdflxjql.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2nokaygll.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gt2qbtlujzs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2vvqsigiy.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2anxowixy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gt2nexewont.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gt2wcknfomc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gt2aowqdhzq.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gt2ueyjesxo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2eciuftfr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gt2golcdvvz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gt2ubrkwwmm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gt2whspdykf.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yebqjltm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gt2ewttpgud.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gt2pakrasfv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gt2uwbcewmr.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gt2bkjmtjyg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gt2xexasgwe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gt2mfjlrllz.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gt2rgwsnaxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gt2deitnkal.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2vtuipjpr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gt2wbuurpks.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gt2brbihfjo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gt2zqfdmjgz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gt2duzjqtku.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gt2gpztzmme.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2jzfgmemq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gt2idckarsx.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gt2edgiwkue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2lpvfoqmw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2gogzbhoq.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2cnnlaflw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gt2gknfucua.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gt2jprybunr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjqewvez.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gt2xvaljcuw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gt2oxpacxxc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2anwqnhdf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ooinfdbl.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gt2vwsusopq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2cgunugfj.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gt2uuheayie.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gt2rnipgcce.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gt2zrgrcayn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2pgamtbwc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gt2bzldoesr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gt2lvwpjkco.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2pagsdjow.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gt2qukogbfx.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2lcgkxdrv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2fmfrwivs.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gt2grjxyqur.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2pxqcksgf.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2ugwkhsws.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gt2mymoyigu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfzfdog.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2gsbaalae.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2voiixwty.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccynzqwz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2pkgebryb.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gt2ghmmwggw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2xtitepyy.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2fcqppfjl.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gt2rhzpsgdd.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gt2yynxbfqs.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2nxhaqqru.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oevwqovj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2sumhoeel.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gt2pbnsejzr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gt2wezvnjng.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gt2ihdyabaw.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2sgpnzmdx.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2zmtbexvy.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gt2megwatzl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsfgbmoe.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gt2zzcytubz.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gt2gakbqusg.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2vtwbntqq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gt2fkajxksv.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gt2olgootys.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2xdwdctoz.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gt2thbijshl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lukuagrp.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gt2xzzwtvoh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gt2iptdmuwe.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2wvqhjpoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2bzxmanrp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gt2pxcgshif.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gt2slzxzves.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2jhvumluo.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntconowe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gt2qvduobov.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2bjhfrvmw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gt2bertfynq.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gt2lkgrksyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gt2jeunorju.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2aeuzmfol.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2litwvtvg.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2fkssmolm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2vqcimeol.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gt2btlrhgiq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2mqbwcrfo.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2hygumwxo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2qslukkjt.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gt2dilifsnp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2dhesejfo.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gt2fscpmmoh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcinuxwh.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2ckdlbtpu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gt2qdvuazwf.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2dnjrffho.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2mxacjsrr.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gt2xeqxufwv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gt2itjvknln.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtdbhoot.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gt2votlpjow.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2fuenlysk.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbaymsrx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2lvapyuvj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ielhsmed.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gt2baltbjoi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wvdebgny.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gt2rnkugzje.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gt2cbhbkzym.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2faxaltpd.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gt2anhmnzlp.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2bofoubnz.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gt2mgdszzwn.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gt2xtgcebdk.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2fyxrndyn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gt2dqghjzoq.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gt2uohyjkcb.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gt2pdeveqib.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2sndskeah.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fkxfzvwx.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gt2paepicbf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uclbyoox.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gt2sqswukjp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2frssnsmw.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdgstqim.html


<!-- 参考信息 -->