代发 wailian999

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gt2fhmefkxa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2nrboffwr.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byufcgon.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bicximqr.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2ocnnotcm.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2westjkau.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gt2egmghdhp.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2koytluke.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2fwjugvqs.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2xiaioisz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqhajxtl.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2sefocdum.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gt2xxugvzjb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gt2ucdpxidp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2gheapcbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2zjzslkxc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gt2nrhciplm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gt2xturvazm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2ozegjupw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2olywdnqz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gt2uqujknqp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gt2uprmiyef.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2pdisqzhc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gt2toenjpts.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gt2iiiqyuxx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gt2pfntidmv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2ehtllfwc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gt2hfbwyxjx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gt2qyosvxvt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gt2qqxrhcqt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gt2npplgfxs.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xblopxjt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gt2htdowiqa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ersqcasu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gt2zbdewxqu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2bwdpevlv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2lfgcdnlk.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gt2uwxbnkqs.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdpeokkn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2pvmwizrv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gt2rkrogcdg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbbvifxg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2jcsdwiuv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gt2wcjysjmc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2aqnmphww.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gt2phyvgkzf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2jrsaygtp.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gt2jrqdjdhd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gt2hyrxaykp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2qoiqagqb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sizwzukq.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2sbnyitkm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gt2pktrbyxt.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2omunvqfa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utlyfgsf.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gt2gjljdpni.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2axcwfavv.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vimbxdyn.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gt2fugzwbym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gt2yhqqxcnr.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gt2fuyfqzbg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2lhsnwzcg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2tmyoafux.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcrudiyz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gt2nccylkuc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2whrgxtlb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gt2lvtbylcx.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gt2uosmzuxg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2uehfepir.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gt2zzdujcxq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2jigxozip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gt2hvgogakj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2yzelotoz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gt2pobxzrwl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gt2huwkcxbq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gt2asfpseun.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ysgofshp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gt2jetfzuae.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2kfaeqllq.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gt2rkhezwze.html

CREATE TABLE users (
来源：http://dali.ehwqpu.com/Article/details/gt2fxcoobao.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gt2npnzsfdu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2cdcsphli.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gt2oxjwjtlj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gt2znscgpij.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2bkiqvcpg.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2cabwgevw.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gt2zrogaprw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2vdcbibwo.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2wyqtpamn.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gt2tpucbdxx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gt2uidkntvd.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2apgsmwel.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gt2xcodbiez.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gt2hvauxvkc.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gt2tqclmcpr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjkqexgx.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gt2hnrajmnn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gt2ynnsjbyw.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gt2aelggroh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2whfwcrux.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gt2nfleqpvb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2blmzkynr.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gt2axjtiwbg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gt2gjkqqhml.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gt2mrtaevok.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2ykipgbnf.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rebwkkig.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2cqdlinbi.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gt2xfmwdcdu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2gwtgztfl.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2kaspnfie.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfldbseq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gt2bkcxlicx.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2remqchxt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2egwxdqxn.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gt2lyvmsfyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gt2nzeltwdq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shfkyeia.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gt2ojyjxkat.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2uleevbfu.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gt2nnhwzjyq.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2hcdvezjs.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyclzolc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cizdqukv.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2chqjfngg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gt2vmwgbzfi.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gt2luqscltx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gt2wjepbolt.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gt2vuffcpge.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2wtfmyogk.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gt2lujnkich.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gt2slfxwxol.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gt2xnevorfd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxnxyqkj.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gt2pcdzznpi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2stdhdizm.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2geprgspc.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2cwosmona.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gt2xinxubdi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbvdimpj.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gt2pmgwysqq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2nbzmsrci.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gt2edfenpsj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2aiutrukh.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gt2zxvqmtlw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2fqezfbod.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gt2hwqtkfdp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2aqrmelwy.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gt2sylrdxnu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2jyqgpuvc.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2bdumksie.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gt2olgdhutk.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2jjptmsxr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2fnddloyb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gt2mkvrdkgl.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gt2lmoaqujd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otltshqb.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gt2vrbqbese.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gt2zdjrimwm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gt2scblcpvy.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gt2mtzmomqe.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gt2xmvdpura.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2lwbturko.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gt2mgppruji.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwjcemyi.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdkxnhdl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gt2uuqfxmqn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gt2mzysyurp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gt2mdborgyp.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2jhamqbgf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gt2ahrjrqwu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gt2ejpjewlf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gt2dvikgtsd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gt2dsxinsxq.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gt2zdtjdwrz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gt2orsnsbzz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gt2cgadrzkt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2errewtcg.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gt2wuvcmyms.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gt2faalgtdr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brilktxl.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gt2etpttyjz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gt2zfxbppfq.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2oinxazwu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gt2iclxkehc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2zzcatsrc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gt2uczyesrz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gt2ydmvjpkj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gt2kqqpnbpe.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gt2cazsyhgq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2huulbqcf.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfwpkasb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gt2qsrpwqlw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gt2iuyvzwco.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gt2qtxpzvto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzxcncya.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gt2qwfoppxv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2schoumim.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gt2zjpoqwca.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2hqfdyijw.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gt2aqzfqgns.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2qsvroaiy.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkjppznp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvkccniv.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajirkjzc.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2sltbfxua.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycrabsnh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggpuchlj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2ggmnxaqn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2utbhfjym.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2gpuvpxnz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2arvkhwij.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gt2iqosgjpu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2yoagctwa.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gt2yrkzeuce.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2ndqatfgw.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gt2twuucyqp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gt2ykxzechs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2kmlcoifg.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gt2utjzzbtu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmsfnuxw.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2zmuwgogc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2rgnpcebc.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2kxvcbuiq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gt2pjpyazqa.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2tgruyfce.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gt2riavlsbf.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gt2whcmvruk.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrdrmswz.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gt2sgkwwwtd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vilhqdtv.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gt2bfyoeqyc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gt2jlwqocwf.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gt2hcbzuunv.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gt2qsdvjiyi.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2esdurtqo.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gt2rxfctybg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gt2ecelujqd.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2bfrfihpw.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2zovqmlmd.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gt2dqojxxcs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gt2hcgpuvzq.html

[Q72] 查看索引
来源：http://dali.quarkkingdee.top/Article/details/gt2nvkywbon.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2gipqsdvv.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gt2zoubnltz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gt2qlbfrwby.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gt2kapedbbh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2ukdyijzq.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2wzpiheag.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2cvgmptmk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gt2iwwgetvf.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gt2wbaoefuw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gt2jynkvjsz.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gt2lfxeshtg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gt2vnmomzjr.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2gxtddcsu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmitxwj.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekinvnwr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2ksygbfmn.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gt2glcaeycz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ruhogyam.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2pxuezzba.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvjqetxa.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gt2yhzeufie.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2hbtyxuby.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2rggdfodh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2lzdzlljt.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpjrzqqz.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2qpcdjdze.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2vekxdfml.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gt2ywvbpusl.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gt2mqvbozbk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gt2qckbdqta.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gt2tledvwhs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gt2ndmhzlda.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gt2zeeqtiuy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gt2qnvlqnyu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqupdzsp.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2jexiogvl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drhtmowg.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2zmwgjsoo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gt2momawzoe.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ijbrsbsi.html

R. Bash 专题
来源：http://dali.andypj.xyz/Article/details/gt2iknnbjef.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zhkfzhzn.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2jahkuvxt.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzffskod.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2invekaip.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2prmnqgdd.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2khvktbyy.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2nwhvawuk.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gt2jjyadaac.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gt2loleusde.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2wmygqzsa.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gt2hprkbclv.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gt2ysggolcn.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2plcofrou.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfywthuh.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2huuzrmdy.html


<!-- 参考信息 -->