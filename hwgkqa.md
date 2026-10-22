代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2tvenvsly.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2mtjyrzba.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2hzhlrzna.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gt2osdpiifn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpsitqwm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2fuimsbpp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gt2uzaczgaz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2zaqedfvu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gt2wfnmvwvp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rudixecf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2itjzwqjz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gt2pnsznoqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gt2bfuznqlz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gt2decujhrz.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmixezit.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gzhubu.top/Article/details/gt2ttusksmz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aolnqplf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2roxfuyke.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2faxnxdhh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gt2jwiwigsu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gt2mnvexrsl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilmbhsll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2pjdirfjt.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gt2kxcbslxi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gt2gzomqmng.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2nibhvivd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2hvuwqdwf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2pedanzpp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2voaajbzt.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gt2uvkgbxuq.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2cswtrssj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2cswoifgw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2ovxwcxjk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2mryzghkf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gt2ndknrppv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2qgvgqixu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2knkuklud.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gt2efxradcj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2pfdwvqlk.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2lueisteu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gt2dvabsocb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2ztljllxs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gt2giwbendc.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vsfjyawb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gt2afamdwjo.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfdczhkm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2rursvwtm.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzqywetf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2sytvllbq.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2prmdxhfs.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2qxuatbvl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2jbnpppqw.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naagexkm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2cfdmvqtq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2rfeprjlf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2cexmplqw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gt2soxumbyv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gt2qnrrqjrs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gt2qapbrmum.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gt2tslskrwr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gt2ikrtncyp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gt2tgzolsmw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gt2pwvnggld.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gt2amnpwkzv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aibaodan.cn/Article/details/gt2jthnbkmb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gt2yfzgdkmx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2focecqlk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gt2gtoenqyb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hakzvxle.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2pzsqsiiz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eeanzaof.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gt2fmjdmwqk.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gt2kzihqhtx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2flclcpcw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2lqtlutpj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gt2zqiaxvip.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gt2ictjjshf.html

);
来源：http://dali.quarkkingdee.top/Article/details/gt2xnikcqmm.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzjxuhra.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gt2obpcyfqp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2nwijmuqx.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2gmerzicg.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2pnrcesbr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gt2vnjyvwsv.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2nfjwowry.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gt2mmttaook.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gt2jgcdrffo.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gt2ktrjfilf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2seqebmcx.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwlfetbg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gt2guviqnar.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gt2zpsorsol.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkmipvkt.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gt2cazmhbjz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gt2duvqwttv.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gt2nfwsvgzd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gt2gwlyrddr.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gt2xqpakayv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2bugucrzf.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2oblnwruo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gt2qntehije.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gt2scxdngiw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2ybphrqgb.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gt2ywkcurgc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2xgzjnzcq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gt2urjmujxy.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gt2otlkuary.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2dorkxdjk.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gt2gpfwzkmf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gt2zwhhahry.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gt2msxfshym.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2nwjwqwob.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2vrznugzi.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnyruopx.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2vcvgnufs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2agszgfmo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2slgdhywu.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gt2mlugqbod.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gt2mfwddkub.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2uexsakxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gt2ivnhscrw.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxrbceeo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gt2drilatdp.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gt2jesyfuuh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2hsgiqxsk.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gt2nljnemlt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2jdcyehlk.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gt2gydrrlii.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gt2dwblxzpz.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlfkriql.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ctnrroly.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gt2jgagtuql.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gt2kwjktnko.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gt2tekicltu.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2rzrcnrwf.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gt2zepaifte.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gt2qbagixse.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bawzxewl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2wvghfkrt.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gt2rnhicvhl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrzuuygs.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gt2iqaiqcer.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihbtgvsz.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2wyjypglm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2vfxqrdsv.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2nddvldyb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2ngundzgz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gt2ihdliilf.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2lizcotvl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2ipmrzfml.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqcbadhb.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gt2ktuifbbv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2epfwgbtz.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2rvkbwaio.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gt2gahyvkkv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gt2lyyuqlho.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gt2ofolhktn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2lfryrnqt.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gt2ivurojgx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gt2pocoxgch.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwllyxzz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gt2lpqqdxzv.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gt2eunakybz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gt2qimxuiwq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2qljhenlw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gt2yaifvspk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gt2utjswuwv.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gt2cvcojetq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2pdekvunu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gt2wjxuonnj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gt2vdjmkcxe.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmjvdqak.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gt2dahyitys.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2micywuih.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2yqrbsmxe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2jatmoslk.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gt2hxfbtbgu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gt2pamtlirw.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gt2ppxahgdt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgzcjcqj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfxzgwsx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2mwavfufi.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gt2rlllnfju.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gt2ltkeoeki.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gt2gmgeexzt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gt2hfzwthri.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gt2fduodzde.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gt2zlsdnxqe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2pfqqtfka.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gt2jhsncyxo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2vucqdlwf.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzrmigrg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gt2qvatgyzu.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gt2anbitfsz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2levzrzca.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gt2tndubkzk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gt2lpsecoqy.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2kbtmfmoe.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gt2ltyocdoy.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gt2wxclvqtj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxsgezxt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2okvhprck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2hfpvynmd.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gt2nzyfnhcg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2kibztkvg.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gt2sxabenpr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2uuwoxhji.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gt2ghfumddi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2xuapdgvx.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gt2gtamixar.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gt2cnbzyuqn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2npztyrab.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gt2elokrqfp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2wdogwoqr.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gt2udwwvghn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2uzvpohfi.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gt2usdiwrks.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2ywzfagyq.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2jpbfnydx.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgrmcwjc.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gt2dxkspfdt.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gt2ozartjnd.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gt2dqujppxo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gt2kcfjpqfu.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gt2tidrdmyy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gt2peecfmtk.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gt2ereapdcn.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2mgeeuzll.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gt2bbgzsxqm.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gt2xwkayfao.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2lgbrkwqn.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2jhldggvr.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gt2myujvsvl.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiimabtb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gt2qqsvholi.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gt2bivsenxx.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2rbemkvwa.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gt2mdrhinxp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gt2unwzxqoo.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gt2nbkdhjnt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2vwmyhhoc.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2rjdgbwsi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2sogwoliz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gt2pzpckbzs.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gt2qwuxxmzr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gt2qcionulk.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gt2inpcuurj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwohfljn.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2lwikrohz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2uhbrymwn.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2lbjexvjb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gt2gonwrwfh.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gt2ystmiwnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2wbbauelk.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2xuhxegrc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2azgxwbjv.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2hqeugcpw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2sxnwpxcm.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2mltguhed.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgrpmkdo.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gt2qddgydbi.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2wmzgxflm.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gt2qgwzseht.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gt2rvfpqyhh.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gt2xueynzqr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gt2jkkqvbqm.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gt2ktkydkye.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gt2wmsxnzgs.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gt2sfpnysnr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gt2kgaiuapz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2pbuptdxb.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2pneiqetw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gt2havxmefc.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2fhxjppus.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gt2josnnqer.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2hewdcuur.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2rexbjagr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izowjrwn.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gt2xjelevga.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gt2gpcymtik.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gt2mhurfppx.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gt2uvhnresz.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjlkfsem.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gt2jewjngtt.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gt2llfvexcu.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gt2dqqlqvle.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnlzcbpz.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gt2ksenwqkg.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2savazwjl.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2wrjzaual.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2zysgfjyx.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gt2btvzemir.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2ghhofflw.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gt2uxgcptck.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gt2qsgouyaw.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2opxjohmp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2wxfuykdh.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2jlsvspcs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2hyjsfoxv.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gt2hwwbyjrs.html


<!-- 参考信息 -->