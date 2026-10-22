代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2mtdzfnva.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2yvxxumcx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2gzusrmwm.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gt2jmcsmvtq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gt2anxbdgns.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gt2ikadqzrf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2ndojnwjs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gt2xbyuvwnk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gt2hbufrlxx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gt2hhobkzfd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2tujdkkwc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gt2hxscojsp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zrqxiokq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gt2gcboflps.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gt2wuohvhmw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gt2kzfdereh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2pbceyokc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2hdeqmvyn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2srrjrhhj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2sofpmfhq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gt2mngqhidx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gt2wupsjfzk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gt2tixynxed.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdjttiq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hibplasf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2emrdnkvo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2joszyijk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2uzvsjyoe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2oygepavt.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gt2cjpoczcp.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gt2zyzjkswx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2udglajxk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2afafdrri.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gt2ijttkefz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gt2bnhrwbhn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gt2uinziler.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuneofl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gt2lqtgvsjg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2debcmnje.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gt2ltaarscr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gt2bvakmled.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbcmwbyf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gt2qgypdqkj.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gt2jiueegze.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gt2ccahmezb.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gt2kkiwuosg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2lpxrikxj.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gt2hwxnuyij.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gt2wgbrtxuo.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gt2xhgyuybc.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gt2yxdxneuv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cqqwz.cn/Article/details/gt2joecrfqv.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2ivmxdzsy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcwznnnz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2mgkxdsvq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gt2inwxshfz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gt2fiowvbku.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gt2dvoyrovb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gt2diwzvhoa.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gt2qeuwwuyo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gt2npxngcvo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gt2ojvrrgui.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpjqybsl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2bzejupfi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2ieodsmzx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2xnfwvzwf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gt2ndruwbba.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gt2hibfpxwp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wfwdktjp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gt2jnwdlvac.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzohbmfa.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gt2ugjvajgm.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gt2dmoburyq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2xoszfvhx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hybqufhh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gt2aujotnwv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gt2jubndenz.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2sjsflnor.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gt2svbtunpk.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gt2lkkvnzra.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gt2sfngynxq.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2hlqoseqq.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gt2xgajbnmz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gt2szymiohb.html

);
来源：http://dali.sysykeji.top/Article/details/gt2zbwgcszo.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2tgtfkioa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gt2excbhbad.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gt2woayokcw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2mhjgldcj.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2ovitanei.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gt2blfhuoza.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2peynggdm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gt2qkrfjdro.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gt2gcxrbegg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gt2oglnxebo.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2pfffnaqc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gt2bexjmqdy.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gt2lepkidcw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2ydxszizm.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trllmagy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2fnyjwtmj.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2jdbcxycf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2smlsgwrl.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gt2nyqipgnn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gt2bdrpehfa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gt2wiwofsqo.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gt2sshmmmvb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mscibynx.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2pyotjlbx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gt2rvetrvbv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gt2wpgoypme.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2fbivldsq.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmodlkhz.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gt2xophzpdf.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mvdwegll.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gt2wwmszbca.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2vzikkpwg.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2knjetjfh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gt2udvzxsta.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2opkaathi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gt2uovvsske.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gt2quivulja.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2zdaqsjld.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gt2oelreevx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2fhdlgwyu.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gt2uhkgzglk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gt2uheqdxyt.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gt2zsjqxsry.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gt2shrnwvnc.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2ughlrese.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2duakgezo.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gt2biqwjwzj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gt2oyowkdho.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gt2lgjnprbe.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2tuislybr.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2nwwaqjrk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2jutnipqt.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gt2owoxsmoh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2clhowjjh.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gt2welmbtft.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2vkergrqg.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gt2hfymqjen.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2nbrjqzzb.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gt2vcawjzyq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2aypbdtja.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgdzzqui.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2ijnyqwuq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gt2xbwkelyq.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gt2ioashtqm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gt2qhiifgen.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gt2sxdbzaqj.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2vthwtkuk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gt2fhwjpwvp.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2forbisxm.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gt2sbnvewxk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vylaciqv.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gt2uxorrhox.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2qxzwkpul.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gt2gceigeww.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2cqkexuop.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gt2kzqksotc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gt2bhvsvqsl.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gt2ztauxiew.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gt2fdqdrqdh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2pzfonabc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gt2ukiyveto.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gt2jpeysbai.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqbtdrgr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gt2byjnkspf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2losjraiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gt2gmerqygu.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2dflucpxb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afweztop.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2yhgnnwys.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gt2xnprcnlm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gt2tvfaequn.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2lgngnjfd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqcaqmvp.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gt2auspkspi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2pvblpxqh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gt2zyfwigyl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2wclxvrbi.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gt2gonzmneg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gt2uxjjjemp.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gt2tkikxhzf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gt2veaobtgs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gt2xzeoesvt.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gt2qrbqnpjf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2fmtwsmyk.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feoosmtz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2uaebakfl.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gt2qrdipyoe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2pzimeofh.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gt2hptjgprb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdwzsots.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2ylpsjgfp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2stajisie.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gt2dhqfrjgy.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gt2suytanjz.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcykpbkh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hakdaiow.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gt2fcmhbauf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2xlwujvsh.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gt2jziwmstx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzghgnbw.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gt2fxhghrpz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iboxxqce.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gt2opxgfgfo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2aufovyzc.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2mhpoorsj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gt2affpivfv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2apiwwlid.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2wxufevvl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2svsdaumm.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gt2davhfwxm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2nlmrvjhq.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gt2pxvcydip.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2drixhash.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gt2ftrkwrdo.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gt2fjvkbfcl.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gt2xzcjufuo.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2mogebqvf.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gt2yzttlleb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2alzvlgji.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gt2ftuvpkzw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gt2wrvlwuwq.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gt2hhiqehjt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjhkdqp.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2hybhtdxn.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2madjwzzs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2lgcmjhiu.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gt2jjaajwmi.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gt2gekdkfug.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gt2ywkcwpoi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gt2authjvqs.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2jmtwhuiz.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2zywgpdrb.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2tyfwifvn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdfxclaw.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2lqjiztdw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2hblfozcg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2amgahoxu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2pxszvogx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gt2ebqifkib.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gt2zfychuzy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2ueetuxji.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gt2pmaqbwaf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gt2uyucuyet.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gt2ksgpvpec.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gt2xdgwenfl.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2ybldhjrx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gt2fipoduup.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gt2fyuwvgbc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ivrpeeix.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gt2ucgwsqez.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2pbuvgqqj.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gt2kbbaufis.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2avnxabrk.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2hjhgehwl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2yvyiocme.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gt2kojgwwlg.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ktnvntsf.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzazawhq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gt2pfeedyvg.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2pzqumovt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gt2xjpexhol.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2purqhixf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gt2ypuemmrh.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gt2fxpgbmxk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gt2fhjkjnhj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2gpyfhnae.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gt2bltufwhz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2xorvqwmi.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gt2csqmnjka.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gt2achtibdf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2erfesdcs.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2adnkocoj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2anounxtv.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gt2zymulfis.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvlsiacu.html

set -euo pipefail
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtzoztee.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gt2ovgtaaxq.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2cpftwhvp.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gt2pqxadqbe.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2xieopzdh.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gt2yngqbxxf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gt2rmcieajg.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2tedseayx.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2yslxgtwz.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2crbayzca.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2fscspvtq.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gt2wyxoigys.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2kpwmpexk.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gt2fuhohnpo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2vhipstiz.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2hqgbhseg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2gwemezzj.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riplvsia.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gt2ankfvezb.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gt2aqvtxrgd.html


<!-- 参考信息 -->