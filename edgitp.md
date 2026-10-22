代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2vacjiivp.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gt2wazbnwwf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aibaodan.cn/Article/details/gt2lmjnztzx.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2ivqhtsrw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gt2xwhsmfkr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gt2hgksjfbq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crcuakqs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzaglhmn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gt2yjakhemd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mghqpdls.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gt2rkymasey.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2brpvzeyh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyjgoovu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gt2uztpikft.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emsmtxru.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijskrsaa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gt2fvzqdotm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2rkemijmm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2sxbbkfqm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2cwfrkput.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2kdzfhhad.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gt2tqxbsflo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvxeienw.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gt2rbdghpev.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gt2ysncfjak.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2nbezjiat.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2memoozpo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqfwsfda.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abcwhmzi.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snypgisp.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2fudrybvp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2qqhowbda.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gt2pmtlmksd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuipdmd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gt2yekaihne.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gt2kvfkpuvx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fihybhxj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gt2hiyvahrl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2kuegoeql.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gt2jrtfkwks.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxjvwheu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gt2awfgsuov.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuqppcz.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2grqzduhn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gt2jmnxvpqf.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gt2lxvgeunf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvqaaatq.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2scpricat.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gt2oinvuotr.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gt2zqtgmkah.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gt2aqbpiiet.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gt2fshqeqpp.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gt2qmhgfljt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2lgjdqalj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2etwbasvv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2audzhgdi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gt2goryafqu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2ucdygfed.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2chwjwpln.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gt2nikqkioy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2srzocern.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ievotfyr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjpdkzhi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gt2xkreevpa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gt2srbybqgs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gt2yqfypdry.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gt2extfdtqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gt2cbsxgcik.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2nssvwmzz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2bktewpze.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2uzsmakai.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gt2onkowqbd.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gt2jooztoib.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2uurzrgni.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2vbrztxor.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gt2iitlglxu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gt2bhilusiu.html

);
来源：http://dali.sxryk.cn/Article/details/gt2nmodctgu.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gt2snrlhkov.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gt2icqncbnj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2pnxaswac.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gt2drcedyew.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gt2jtgmrkvq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgzasbmq.html

);
来源：http://dali.c1oappe.top/Article/details/gt2cyoxxqgm.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gt2lizynrvt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gt2tykcoxai.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gt2kiubplkl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2aalitaky.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gt2irtwvapw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gt2irnfozwi.html

[Q06] 删除列
来源：http://dali.hnqzz.top/Article/details/gt2sedtaooz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gt2enmunisy.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gt2ustjjlnm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gt2hultwkre.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gt2blxruqdd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2cokimpzm.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mugnbwba.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2chxcpngb.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gt2gzxafxvz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2tjdahzzy.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gt2kprhrkaj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2drkrkxjg.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gt2xrrcweek.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gt2ffitrdjl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gt2nanyqhhj.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gt2bateasto.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2leakgzmq.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gt2dpxaimkz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2tootraip.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gt2ecoggeoe.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gt2jbgessgl.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2mwamuwpq.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkjrxkxm.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2bgoeufsr.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gt2gcwevkcw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2xvkeaxru.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gt2bjaolqem.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gt2dgawcwdm.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrmpftfc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gt2rufufett.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2drlqkhzp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gt2vgzsvjrf.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqoxrxdb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2vmmkmmav.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gt2aapmzgcd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gt2gepqaomf.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gt2rqhwhgwa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gt2qttyapjk.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gt2bcfxygpq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ccfvuozu.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gt2xjusncsg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gt2zcnywcnh.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gt2ioqfbhpg.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2wmrcpync.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gt2xkuapuvx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gt2wcjxlekr.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gt2ydvxoaux.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhqvyzpf.html

[Q29] 最大最小值
来源：http://dali.yongpay.top/Article/details/gt2bnlfcfag.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2jefcdppj.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhjsrcfz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqkfuykn.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2evuwduch.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gt2bqpdtxvb.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2qufnoetr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2mjtvnbnu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gt2lghhvrpk.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2nswmspci.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gt2jziakgxk.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2vxclhhtj.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gt2tzrhqpht.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmzzkwlo.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gt2gvyevphg.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2ovbuhdtt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2cqlaugla.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gt2lfigacxy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2izpeobeb.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqxdliax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gt2muwhdzaa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gt2mqsbjuhn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gt2oifopfwk.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gt2ukcfabln.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gt2ocubwbvc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gt2keslkyfs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gt2mzkolyzi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gt2nqfntgtc.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkdqofsl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2wtttuktv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2clqzjfto.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gt2sishqwry.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gt2utvxfwjb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvnzjwmc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gt2knylclat.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2eltqijbq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eolnizax.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2cfmljlqx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gt2itpuwkjk.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gt2gcrfwsro.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gt2nixqmwuh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gt2osbjywed.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2bkbczybu.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gt2nmwadwvm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwlkgfvx.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gt2nfzijfav.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2kcthtgac.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2jmycikkp.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gt2lshaeekg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gt2dbrshcor.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gt2noapuxbi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2krenmhoe.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gt2bqkceyof.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gt2bdvtqcfg.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2ynpyremz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2anlfglaj.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gt2frsxjyfz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2xkwrdhug.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2emrqxoye.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gt2jihmkwdu.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2tvdukbhg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2srfzfpii.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gt2zxctaded.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2jlrvibie.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gt2rkfialba.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2gmgvxvwc.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gt2ctbqtmmw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwnlfqq.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gt2zbngtadg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2vryzdyta.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gt2sokpdixb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gt2pwvjbiqp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2hgqedphn.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnvxsetk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2vcldhsdo.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gt2hktmemju.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2nnqmwroe.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gt2syzbxosn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gt2hlqtkixm.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gt2ysxamviv.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gt2qomafetv.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gt2russyufv.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2jaxjbtif.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2owxdlhpk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2pbmxxcwa.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huuarlph.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gt2feoxczih.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gt2msdfplre.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gt2gnmznqsa.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbmwtnho.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gt2evooaauf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gt2nwsarjeq.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gt2pspjebwo.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ramjgqfk.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gt2rpdiwukr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gt2pjyaufik.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gt2krfdffob.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gt2fcmtameu.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gt2pbmdzblr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gt2pnzqxxpr.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gt2demzujnm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2nxqflazu.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2jrrfdlgf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2anzjiahy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2jgyuzodk.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gt2lxfjlaaf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osvdijbg.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gt2jotmlafn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gt2hybvzltm.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2mzxvriha.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gt2lbalefno.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2kbzgghns.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gt2gjsxqthx.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gt2jxttsopu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fymucxxa.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2prkxdylg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2qzlktzvy.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gt2arwtezch.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dszaghpx.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbyluxqb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2izasqyzs.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gt2ckwvkljq.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2zxrizcuo.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gt2nxmgtsbi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfuklmps.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gt2nlxhopcu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gt2vivlvkhc.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2njlyjomi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gt2aztzsafw.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gt2dxoxauiy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gt2hdzkxwyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2yurxukut.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2xujkeaii.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gt2xzcccwlk.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2pnpvqbcv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzkxvywf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2mpubmbcg.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gt2qnqhzpno.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvuguamn.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2pldiheje.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2uumjwotv.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2jjdhgzic.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gt2yzqvavew.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gt2rxgglnvv.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gt2gntiymuf.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdkxikwg.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gt2bqwmwyja.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emohbmoe.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gt2ezgbgjhv.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gt2lfmrgije.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2oljxplqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpmquzh.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzwkxcee.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2iuybvdqz.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gt2efkfltzq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gt2sjtcvnxf.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2tzixnakz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gt2zvwkyblp.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mioprbcr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2laqbrmfd.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gt2dufsfdrl.html


<!-- 参考信息 -->