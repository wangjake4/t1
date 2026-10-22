代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2orypicgr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyirifns.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmovwjd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2muhfwwlj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqdkbmy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvrznew.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaogszh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjvdoea.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxbfhns.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwwrqkb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jsejufnd.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fszdaeau.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhmundt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zubkbzau.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfvkhbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdmqahd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfwnfjo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eudemlyk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpwsxdj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbgregh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2werugibm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hndibicv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaiksoj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbfzacy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdwvpde.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bnahixhx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaocfcq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdwvuuz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uksfrnna.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuhcqmz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2osmkaras.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2msetqiik.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eettmvqz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvwloja.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzvmxhq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpmetcv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlghjhr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnjaqeb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kusqdvxx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujyrnol.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnyecck.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgqefix.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpzkfzj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcoewfm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxmkceo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aczfzlwj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhqifjm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fksmllgr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2giiighdp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqixfrwq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2edxuwztp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oquepnjs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eycyzzhm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ureycjne.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmcsste.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfrotas.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzkgwan.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpcbwcg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdwiogq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmdumrx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgryzlt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbgglns.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fkocpxir.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxodrkj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kgblttfl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gisoezfj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlupqqci.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykevcpyp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tubrnelp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oijhcjti.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2idxanvon.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2enjjgmwv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2paxuxctd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcptyxv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ghffnbdg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbyxszy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ybztokyp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yutizrnc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ljijaenv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqsiqgr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjzlkql.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iisdwvsr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjoljzi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2adnrhkcj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pseyuzni.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdtnzwn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbuzncb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojicgdja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbfcayl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2njnvymbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2badyjwdp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ceszquxq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvsjzhl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnhoiim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2weluculr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfwvnlg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkpgdji.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyzuvcu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjxxvji.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yaolxcvi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnsmkmu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2onubffia.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeihzbs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhzrald.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvyfawu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoiyoan.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnokvtwc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiftltz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlydrisd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnhartq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxivkhkf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2arudabhj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiupfany.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxjcvqd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxycspoa.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kfavhbcs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2srmssocn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cuurwqwm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2olnhndej.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfxieti.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zuanqlbd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jfirkntl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2azjgkmny.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkumxmv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpdlvtk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlxatxy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzsiicf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvnnpss.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vehltchn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wyztemdt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2omsyykqf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqzuvut.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxktznr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijowerjj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2witlvuhu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jljinvqz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiipjvd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdgtceh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnhpdtl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rtztakil.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nouypglo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuejben.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hubcqhjk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vyypqqyf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2epxfelij.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzkngat.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2txshvczl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaxqyys.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iorspaem.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvvborb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzotoflp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pacltwwe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2srfzfizk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2damypzuj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyspxau.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnytglcd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yarbnwvf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuohhnk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcdhshy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2diycmpih.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tskjpsgi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcofdak.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvnhmse.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wypfszqh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqexzph.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzalxuth.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaftqzv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqebeut.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbneprq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2exhuryzs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tguhokma.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ibimqnif.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqedddr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdkzzmz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrspoqlj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulljettd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2euuwlitx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nycrsybd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izywyorz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lljvzqeh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwddkkb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evqsdlcy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pylmcfvl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtejzfh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jppcdvqr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hykkmjcz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcuywhw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flniuvpq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiiuckv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkgwlke.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnetgkwi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qohlhwpm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeyscrw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yygfwogb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rgokfqyp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgtjqhj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2usfnpcvs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwupous.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ylringyw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlolfipp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqghjot.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zneahpde.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrpvjpe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqghrrt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2atmxhgyw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqugcvax.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjynsnu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyodyyn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbfsxpj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqkiwzr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nypacppq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcvhcqr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcopirqs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgmvstp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2btuawsem.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdikxzu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pahxcgvy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpowvxoa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2livvjlyf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdweglhn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtviysxm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylokqduq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnanedl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcqipiv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhxjtth.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xjupvvcp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sewkjjyh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hgirsetd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnujeeja.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvfahsr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiqtepc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrtjmlb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2agjjuzpt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpgtmyv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jewccjrt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqzgxhi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wavhyvpr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vpozdqkv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ciatymxl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2utercauh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgjicgq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oysaktrp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgwyejp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zssjyhwn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2npgpoebs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgceqey.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyptrvj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlauoga.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgptpapw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbynjsd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpmvkdm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2urdwiidh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwofycx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vpedrvuh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgaczxw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyybkeu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uccfgcbf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ovicrjzj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2byqaqgzf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zedcqpxd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xncrnmve.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fzevpdlw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2irdrepmr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiwltms.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxgbfrf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdjedb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gfztywvo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvghepe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aucxacyt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdwbvxj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2acbufieb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwiuqba.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiprdqy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uodsajum.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2npfrekvc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tphehaef.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxrqdvz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpxrwry.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkciwcer.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onfotttr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfuxoul.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvswdobh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2klleeswc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxysspo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdqzfyf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2axxijcmd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbsulrk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhyjhwf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzykwdk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2moonciks.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgyesty.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2njesambn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwrdnra.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbidwol.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyqcvnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjapzel.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2khxvqbet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhtzphr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2razfdwji.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfiafrp.html


<!-- 参考信息 -->