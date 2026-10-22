代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2ecgceyia.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2dhoqbrem.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2lqricthe.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjlfghfm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2iitzwcnt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gt2rizdqarj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2atgpmduz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2vwjddqpw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gt2koevabxi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gt2hydjnyun.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2dukemrqy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gt2thguuazl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gt2vocwxfzn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gt2dmlegxow.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gt2rgdlfdyn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gt2yiondunv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gt2ndxishiw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2pjhllesq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2nxoaltgz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gt2pqmusyoc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gt2dxqkkgza.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2rohjirvr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gt2chxkttml.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gt2sqxtovkm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gt2pnskrkyy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2nhjngdkx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytyljied.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hafaqddx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2lkpsygfn.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gt2fzlbvipk.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gt2ewkesxqv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2ewgpbrbp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2sryeaass.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gt2kweszhyd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gt2mmuhxomn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gt2rboyethh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gt2zxyyuuyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xznvrnbr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2ctshwdlk.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2wnmzjzpq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gt2hycaeaey.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2rgtstpkr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2wtaglcpk.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqhqhatj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2fqthseay.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmzznhwa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2rvxzvnij.html

Go:   if x == nil {}
来源：http://dali.quarkkingdee.top/Article/details/gt2yvwplqpy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gt2izycbnid.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gt2yzpmxnet.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gt2dguzihsj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gt2cgpozczx.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gt2jrzypzrt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2izhugyra.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2kefyubuf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gt2mtlxwtsx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gt2dqppqcmx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gt2nhroornq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gt2mffwrxza.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gt2mnalwjkp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gt2ulrmerog.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gt2ugpvasef.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvjsyovp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2rgnoaeff.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gt2lzaxhews.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2xvncsaob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daxiang520.top/Article/details/gt2fdanompw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2dczkjhgx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ellzbgae.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukamterr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2vwcgsbta.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gt2spttncnm.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gt2mjexezao.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2duirbbbr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2uxlaeynn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2nafsyxqn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uscxgtxp.html

);
来源：http://dali.mhx1999.top/Article/details/gt2xfmzpioz.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gt2yelbgmer.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gt2mqnjgnaq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gt2wmkdsxlc.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2frwpjqbo.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gt2lwdscnab.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gt2oiqjfhxh.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2focohjyj.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gt2mndbakkz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gt2zyogonjm.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gt2tjtkwlei.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2fqqkobxh.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipxinggh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gt2ivxsutmj.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gt2tolphgfw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gt2yijfljdv.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gt2awgmpvxa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2egjsdwnk.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gt2gljamixw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gt2zwysehdg.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cixhsodn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gt2opxfckuf.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2epesbjwv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2omljvcir.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gt2swpiikqq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpwcyxbz.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gt2sjzysgvf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fixcrzqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mquhdtjs.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gt2vtwvrstq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2krbohycy.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gt2iowlkbkc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gt2eytdppni.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gt2vsjmchod.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2igyoimds.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2wvbgkmeh.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gt2kuepmjrg.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2yswjvwhl.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twrwpdos.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffrpesdx.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2vcqgrfnq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gt2uokdbxot.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gt2cxncnbow.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gt2wchzerwe.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gt2nunbdnmm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gt2gpektotd.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gt2ufpcrrkk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqwwetyi.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gt2rdzpegyj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gt2szzccagc.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gt2ahbdesri.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gt2dqsehysw.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2frmsxddb.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2piuhboka.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gt2uvkgqpat.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlkwuyyk.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gt2jvrgtmyr.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2jucfayyp.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vznactbq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gt2nsocwoxs.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gt2yfjehfvr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2hbzdbrfc.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gt2fxxtwkri.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2svozokmh.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gt2hlluzpax.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2kjcnpplx.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gt2nwupizce.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2sgeqywaz.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2rhustzdx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2dmqhivzy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2ouhqdavb.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gt2xxcjgilk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gt2zjbwtolj.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxlzxqid.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gt2prtoznur.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gt2reomebyx.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2gtztrnxj.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2zkaubjva.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2cteppjfl.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2holjonnp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2rlpgzris.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2mbcuqlch.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2whoretto.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yexksxdc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gt2jwfyczxe.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gt2dcalfoep.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gt2eenhyrem.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpglqmqr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghsdgjuk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gt2voorvqhu.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2ofnobzhz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gt2brozqkca.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gt2ejraxhol.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gt2yskibvgn.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gt2qpjjfbfw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gt2oetqptib.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2kmlzmjyk.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gt2ozxsjszk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2cutzloqe.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gt2sysjedfm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gt2sujqdqxj.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gt2uhvxmqfd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2laxbfagf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gt2qglfjhaa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcapalme.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gt2wjnakrdw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2orcokpvp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eaprvwok.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gt2ckfpulzh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gt2fiddfjvo.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gt2qzqouhfm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2sqwpbdfg.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gt2tbmzddjo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2dqeahbsn.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gt2spuyvmtq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gt2yqpseufg.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gt2drhhxilb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2heuuchbd.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gt2aabpgoft.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2nshmstkq.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gt2bnvhvhmi.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2fovjpulx.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gt2xexhmmzd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2gonbbthn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gt2kuxkaeof.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2iwlbhqsa.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2nezzxlev.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gt2xkgajiho.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gt2ykekfpdj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2kirnkubw.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gt2ajbiwcso.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2qfznffta.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2xigrpvmd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gt2wyscfjyu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2hgpmxbdh.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gt2swngonqi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qufhvqhe.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gt2iybrmabe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsitlzuk.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2buiccyww.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gt2kgeltdsp.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gt2frraeknb.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gt2bnuziczh.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsvypdjo.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2pptjtutd.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gt2bglitfth.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2bkdmnkgx.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gt2plnwocvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddehvnks.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gt2fvfvgiho.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gt2kfnngivn.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2jawmfsvc.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gt2nzwdflef.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebamgtjr.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gt2wqitsrqj.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gt2qppqmmak.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gt2mxtmnslk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gt2shxkdhpk.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gt2uxzrdssl.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2ncxarady.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2mouyhhtj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2juzraokr.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gt2yzbnkzwa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asldqmsy.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2dxmjpzic.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2wndqdjki.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gt2iwmgutmd.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gt2vexcdzsy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gt2oshermgc.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gt2bolpcqmu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gt2yfpncsrx.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gt2eifmmrdk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gt2ihsyftdd.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2ysnnglmz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gt2ajhjyvgw.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gt2odyhykyx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2twdtizff.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2wwkykgol.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2gutrfycx.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gt2tozughgp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2vrnfcdoa.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2zjiynkhl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2ehstldan.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gt2gbypluic.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2bevzugxi.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gt2amxhhurp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsvdrpxi.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gt2jgosnkaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gt2aydgwkva.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gt2iznduzvz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gt2nrsvvnrf.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abnvbhrh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gt2hhpjkudq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2xhddskom.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gt2npdrlcbg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2vabjieid.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gt2boxgpags.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gt2athaqbft.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2cxjbivnq.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gt2aobuqyyu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2diywtmqk.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gt2avzfezzd.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gt2xwemwdcp.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2mhgkanym.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2xrjrndtn.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gt2ustyinqm.html

[R03] 只读变量
来源：http://dali.svipenyu.cn/Article/details/gt2dljmjafn.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqfzkmuq.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2duphniwp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2aqalmymj.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gt2gaglplye.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gt2pxkpdtxd.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2bkjdksjj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gt2qpuyukbo.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gt2uxlvfvdc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2zbarzkww.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmuopunc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gt2iuoztlps.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2sylnakli.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2uzjtaxas.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gt2fampzsrd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2osjrggxv.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gt2hpzhrftf.html


<!-- 参考信息 -->