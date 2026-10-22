代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwtghef.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nljzoumv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhhlrfs.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zazcahux.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokfrwpe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhstapf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aziurnql.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaqfkch.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uobnsyob.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpzjsej.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqfewsn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mixcblna.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wchptapp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iltbjnwx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcaaokx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmhjsre.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2btlhmswi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaucrxl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ewabhrks.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxjhlli.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgevonu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbltjru.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpjoupl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfohlrwv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zzctgnxe.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pswcpiio.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rptoxlah.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2urgedteq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwkspcb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjqptiw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2owitwiih.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fobatxry.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2doylonsp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2crhyopxa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjudkoe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsjdtkj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dukroqzj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxhliav.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2csgplyri.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lliivyvw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szphdrrf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2btxzgtfj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcevjyby.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2djtwkmdt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfietmy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnecoxwx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcgrspc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmvojkz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoqjklw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqxxdmf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2apxfjwnm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrupgsj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dgycnynl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfupkms.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcedfox.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmnoiuf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahymyabm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqixake.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmaxkiw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pykhtcbx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdawujv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vflprwbu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rchysymb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaimvgr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqeetcv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cfksnjqx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrcyqng.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2omzloowp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnxpeaf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfpaxlf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vwklwgwg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjszgzbm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiwxnve.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mobuhkks.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqdxvom.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqnbnyl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlzzfep.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlgqsgr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dghddfuw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhqftta.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtlepnu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcjbjmd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eagystiw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpwjibs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcgrwwp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxycevu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iflljsii.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmhsouw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2olkrnhft.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2chwetcra.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2weaksrxf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewssoqp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyfeqlw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gdobmhdl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuljjlbt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mubfaerj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxxycoj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gizvepyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2finpxgyo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wscngryx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2stespddf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnrjopt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkoiyev.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvustct.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ikitcxtg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzxtbra.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2krbbqafo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oycyikio.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oqswfqvk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2shrqwehz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uleipvku.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwbftkz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgdjnne.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfvmynl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbeotew.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvdqwjt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikebttqw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jojfhvoy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzjkydc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2oovpkeir.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvhjoll.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjgpeap.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uonwugoe.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwjtyva.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgncmyam.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iehcqvuz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iatciyqn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fjydslmo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuehmfu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2swppfbix.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfuepia.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sxegqwfb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dgybziea.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnflovc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoxuhko.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdqwhnn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2njfugewb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqismla.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iypdsija.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwvqbfg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbyusoj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeeikvd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whmtircu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwbxoua.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmqrtqv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtyiddo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sesfpxxi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxfnjde.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvktiqi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gskpnzzp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrjuoep.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkjqcam.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzofhqbg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lulcfmet.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gugwaaiw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzxeknf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayddudwq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2arvlfbxp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hatdatvk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpfuvwj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zyafpdvi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgkdsxq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkadypy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgipjyy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfourota.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmcmeex.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oahhokxu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2epubjxyr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pecsmwyf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qatdovkl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2buesvtpf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuwlfhx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgxqomy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfmkrfk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuxqsox.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcczttp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gutmolsg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2slvzdfon.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjnomhx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2egendsms.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mafwgkdi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2riaybrbz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vgulzzws.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgdxymt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkitxkii.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tucerpsa.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sobsdzce.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqshslif.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkqpume.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjucfvhl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzocnprp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yilvotzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjejqmp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrthtzp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbyplyx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ndctvdof.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tircnkyf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2otroqeru.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umdltjgo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdebwev.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkefzpg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnqayrc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkofizdd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxrnrxm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vynbhuce.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2shommajk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqhugqw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxjhpbx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vbagjlyu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmwxllq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbmhkdr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hezqozln.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pijzvsbq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwmyjeu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqghiwle.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fbitqkce.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qchtyhzf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcqykkq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zlymqorm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eqosjluu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihggupx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxetuvx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnptkvzx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdsposk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwbffvh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksupbwfx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmdmhqk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfafmefw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yghyrfuk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zabbrhvf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgvgpjp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgomtho.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwnzgwa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eevsuuvl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2abdbogti.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rznjyajy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxovxnth.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgozwxgg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2heaszgnz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwohmmqr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2scalxoit.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itgkvobc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlyreby.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlymadlx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqypecty.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yusxspbl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzzbcfs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwudqgpt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2richtroi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvcvpzf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdgeeuq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2valrzkii.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2unimezyj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbbzlth.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zirbjtki.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbokhthy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbydthja.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2enjozmbv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxqfdiu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyqpkvh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvphatp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2akeqclck.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwvzwtz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzcuums.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ourccyum.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oomrqzqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bptbdobj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2riojkckt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxdixzd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ohugbysl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsotuzij.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2usyaqnlk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yorwgzhu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuqmbsk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2drwzxcfj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qcregfcf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdssxvp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfururqq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2whqmibcs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfuyfde.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqainqm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbpochu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwvnyxk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tapwkkzk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bunkligj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpetlqba.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsspklj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfvdodi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzpexnz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwvjyjs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfnajtq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjbodwe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dldmnxss.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nuotwtuz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2licojbcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsbilcb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrtodzj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcgwqlb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yodhtcge.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sorlahwu.html


<!-- 参考信息 -->