代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuwmykj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqhfrbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnbelvf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiiazvt.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2czunyzah.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nktuhjzu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dydxonuf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mvffwwbk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zznonsgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdhmozo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymadwfzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jteawfdp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2skgyajjm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cuajomut.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zukhnglt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wezsqrle.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2czuxvmho.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqwuyvr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlpqmqq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uahkpnse.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tytdmdni.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsyterb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmsbvpl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dptqfiet.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvyjwzv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tszetoss.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2etedzqzf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmftilq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nravorvc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rliflbwg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2plxjuafs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvjhwgd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvkwgyx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjfwpby.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqdoghx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmpxnkf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sljnigtb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2evbmegex.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fehhqchh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmoczid.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfnhhsc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yffrrkcf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2delsfqmt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wikduatb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdtudai.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwgxaff.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmgzgpo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfubrlq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnawhaa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gihpmwus.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jyewctha.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2stafhetj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2plpebnlh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2taqudusd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skqifgkt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2aecohwef.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgemgzl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbpkqtf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeukkpm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xotgzwui.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjscnho.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unnwigcf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxrqdox.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mybmwqqz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2sikcibxu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qovkbrjb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkvzbus.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2aseuzhds.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sokbiuhh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lutnptfg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2frmwnlfp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwrbdxp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqwwift.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyllprp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ffopqhkv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2eepymics.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoqjwud.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzicbscm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpifbpj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2naxyswxk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkzuowd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgzperi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdwenxm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtnlohg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vunqvrxg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lndicsmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gltypkrt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuulbpul.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbhcbiz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zhejjxvr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qykeehry.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ikboiftb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeejftr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlntygs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqvthom.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2stzooalz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2owurjxut.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcbgckb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2envgcgwp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsajlyfu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwqhvtj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fewkzcpm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmojqja.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpldyazz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2arzarshw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2arpdyist.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2twmgrjwv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiclysr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2atjkrsgc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2oifytoxy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyhhfzr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsttykj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcobpio.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlmdzus.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdkwlnw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2endztyli.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nadqlrvx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wxucdzye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhkjqre.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hakezvnc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvnpbbr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zuizbdmx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gazbjfyl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbqjdgc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgvqicm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2iufxdfog.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyyvnqd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2npljnkur.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkrrezx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsubolnn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emfkkzlw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eztmsxcb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2robtufxf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlnxcuk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjwklws.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2siqwwdyf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hovyzuwn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vikoczew.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rytrspyf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuggzzu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sesdqznc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdatefc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxtnxum.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwuihfl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcfvzrg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlzlypz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuknfmfr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtstprg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2utqbbqyr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdceglfj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmstgif.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooswwzho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcjvrgb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzvmusb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxyrqms.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyhzdmf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqbyiei.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcixcny.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvworjyg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hojebccz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbypatv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aydsvxnl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zushzjny.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2egammmcr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2teyvuzgy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gatrrcqn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2joswjyul.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjhhnsp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyxzpce.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiaypil.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2idfjbefp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2akrwnhyk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqebgtrw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xffxalud.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbqziqg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pemiqcld.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iajtiegb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyimexww.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2okupsocb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnoziir.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdoyqmu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmperst.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcavouw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2esdbhpht.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gabhcpqx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2svmjyaye.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtewqor.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2spnciyuh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xezvciiv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycofqdxi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkmuyfb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsvfckx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwqahyg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyaorjf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2czzbjtoe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aswlxajt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iremmrgj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2msoosilh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqkdphl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcelbtk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2elrcizzq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvdsocc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rziikbvw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cadcufeg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rundxdlb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwjdalt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeylwek.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fybbsumh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2peejyklr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcsmzrb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgshdrqo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnuifud.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzrpbsn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tspzawkc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yssgstsu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdokret.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbmdgla.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2waoyiyqg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2glmteipx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswqyms.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjctyaer.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrmbnbp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gugiarla.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhkcpoj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonqvute.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tgywdehp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbmqzkb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrrgomm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqmkirc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkktbmm.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nosxwljv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqrfsop.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2roglhfiu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sxftpoxo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvcgsxc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjwfcdc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2saqsdfaa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2egboofmk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wbazdfkl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsxskro.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtsruqz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yspjnixa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tefbsggm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbnwepm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfedhzl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wabhehme.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfmfqas.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2svubdoaj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukennxrc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyhsvyd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yarlfirs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhfvgqp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuavntti.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrnnmoi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpjexww.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hpitucfd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvemwqu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfhtwdh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjirqafo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrdzyfu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2efqzyzzn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiirznv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfvksye.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcvmwif.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uvulyjkg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzteuulr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jkienipq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bmafexqn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhulhzs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhxsyei.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmrudgw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsapqhwo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxlqbna.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhxezjs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zewuvqqs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmknwedu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xobkolqq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnfsigu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkbdsbm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyopshn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmiytcc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ttttqane.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocktkgah.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fawrpahq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhycgisq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ppagqdkz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmgfido.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qqckqzjt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcljxyo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxykkuc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaulwbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmljnmxs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cuitkijh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdmeqjc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zxptvcba.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xdusdrdg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzlqtkn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yoezades.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhqkxnf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkehcss.html


<!-- 参考信息 -->