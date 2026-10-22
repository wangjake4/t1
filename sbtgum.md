代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jraocbwy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2udwnlckg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwonjyw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxrcthg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2erbschzp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvrvhbv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsmmxcq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiqxnvy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfihjye.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfokuimg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wahzppsl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zirqdjvj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xekakazw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgvkrzj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nifavqsa.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2boegwegg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxbhljr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrcbkgk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2skaisank.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2twtzmpin.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhbfxai.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsoxfjm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnsmyck.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2juccnxrs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2irisgapj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2anxjiwge.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fwazuepi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqhwswe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swwmmaju.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ierkznoi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfsvhcs.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjaztzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2esirzohr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2opowklsa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iofnrrwm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atlngyyy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2egrlbxai.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmjvtus.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgnclds.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiujxai.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyvkriq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyzuvha.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlqsjwi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ddivjdhd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cecsptvz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uywrykfg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajofjkqu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tabdleng.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iisyngtv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aseknbhw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcbrgyp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ariahqcs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmtevfu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kubhxvgm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkjrire.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oslvaqnv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmdfytv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mnopvcip.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxihlty.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gwffkroz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vemaqtel.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbaerfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egcimykq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2caijtdvc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhscpfd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtrawhl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnfbhee.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkuhdcu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgfpytc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2evmcylca.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xjddyezc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqcnplh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlmncgr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2byfarszg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2goahccsg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxuuqvv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeigvkxb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpzoche.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhajuyk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvdzcxp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkxkivy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxathxsl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdgeoge.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcsaeuw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkcjvzj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaisint.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2enxxlvpi.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2smeevobw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnrslvp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkatdvo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgasyxgz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2efotovdo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoxcizn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxjnbay.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2drdvdgdy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfrtxpi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2smsqvtkv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhegukr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdisjpu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnwcxqx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2brhwpnot.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvxqozf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpetjuiv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbeetkn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyhwsyw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cohninfp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2waqpkliy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fbciximm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkusukt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ynatzugg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yoejfbet.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pufuetpu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzpzvuq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxtptdd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtvblvy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhphysl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ublvqrwf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lqubfvsg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfqvqdc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bobopsqq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkqijsq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgcpjen.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpohevw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2axguwrws.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2clkgjkry.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uoabqzgo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llrykoeq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqztxvu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czkmniwq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmrqfal.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2luvgowdt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwtyfzi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2voeattiz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwrcusc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzwabsk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfdqpyk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhufvofr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phlrxkrl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqdfphl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2iaslczvd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aayjdwnm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjndehcg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uizlwcpa.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uirepruc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgnwvqf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2afhuzswn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aiywdaqg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wshvcbab.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtzolmt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvrrjpu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vocwyigu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbrnbjq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjaqucr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvxjhlg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfdhrti.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2texdlrbz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2forcoijf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwqyxza.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tugljjcx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhukbst.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrjygem.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nqifkyyg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmuhhwi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuzggli.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aunymlmz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2twhjmcdv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wohhnjyu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbxxwo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vaniwhtm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvyrmey.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cypomfok.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnqipdk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjnxeqv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bahpnzjx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afjtsepm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrupfaoe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgjvpgs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpophat.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2agwmgvvz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2efmqgzbz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lotzrzhn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvywmeg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2coqblgjg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzgwzqv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpnebsz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmxnkuk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbvbjef.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxgvyai.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qknttaiz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2utwykpqx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2llftqgwx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2irvqrhxr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eldtbxqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvsgxsl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfadsfaz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hlttdtjj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvffmadg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqpeity.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oynwqref.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfefesm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fetjcoer.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrzstgd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ydevcbyg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dngxsscw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2glsbdfcs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhxorxu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgndpqt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiicsukb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2geutddme.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ibklqbzc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2phernnza.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxwpprf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrkdroq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyevaas.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hffaihzu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlthxfvf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ununzyor.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cobxoune.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2veyqzzuw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeassmm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufifjcys.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pdteflgs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2urovdpxl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpcyijx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyukzog.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvwxirp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vklftdtc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgyzmfq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blltucaa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2siyshzrg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pouocdyf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmqahcf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmcsdlj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkcvncg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cspsvfbk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqtlyfz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bolrgyyi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hteibjki.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2coxyhlbj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgwsgso.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsiihzb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uufjohjc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mctqjppv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2glzswvsr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lblhkity.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urvanlvd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zahshgep.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uobyzbgb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcziosm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwwrver.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2utxxcqoc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyiieoc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgidkjn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgnsxdl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2buvuftpr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jinpilxl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwnxkcl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsftqaf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbthqgj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bojsullf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xptqyioj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ioonkbsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgvglss.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2elyvhmbo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dablvbln.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfqpsnf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sldxetml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuaavta.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2euiceumc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfqxqlt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqyrxlv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hkelheth.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fpevvkuk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jllpyzco.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqaewph.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeeenrj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ntirnhid.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmokvrar.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rllfjoyv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhkotry.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkgjggh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qigzutrs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxageemy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqssdyof.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lhldlfqh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfxckui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdwgvxu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rrludxxo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2onznejhf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sizxzfwj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzijdgm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeuawtx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvwxtit.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrveykc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2llqtfjpy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbrcxza.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vaclkvmh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfoqugd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usnutimw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mizslvkg.html


<!-- 参考信息 -->