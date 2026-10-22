代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqkcrlc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmxtljj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frkarnal.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xomcbeim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshryirn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2izmkmbzu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrszjeyr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvvreut.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncucptxc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzxqqzh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwaaggd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiyqyge.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkeunma.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfqhbhn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uojnryev.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uteqwfly.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ludnemaq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyjoebf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyqpbsg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyhpxry.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2riwdbvdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djtcptzo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iarolzmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjduvohc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeplomw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqhhche.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oqibgqgh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcitsanf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhhsata.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysucdfpn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2egphstoe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyqmmcw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwollyn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2shiatune.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhruvnn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwrutov.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgosfcb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nolbiqqx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfawfcm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvdhdxn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2idxjqocw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwcacrn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rynlcqal.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ullbyovr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqkylgy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhauuesb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbkmore.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqiqdcx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2enmjhrij.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojnoxqi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlsjwoq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zehmuqvb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2prltrwca.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyfzbdy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2scolabyv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnipvbdn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjawszyb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zotagznx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oulvaikg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfqutj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qudxlslx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvpucrm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnyzfjz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhydxbs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqlrltm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qmejjzkv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkrcdiw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlkmuvy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kivcellw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlvjzyc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2atmhuefh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxptomu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iesarleb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmysbsws.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyactwwq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nktyrvpl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvlreix.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnbilcx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmhicqn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtyepno.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2euopszso.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvcnbww.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbmxezb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uviwwgyt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxcvchu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jxntamrh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbjthmu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgmvaoi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdahuxw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbntdvub.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjlgicw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdybhnfz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvxsaae.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2orrlzypt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2odhdppna.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeozcdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hybcxzix.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2iijksfuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fandamad.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2khflsswt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uvofuslt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbrzdxw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzepfddk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzhrcmh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bcweiggl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfpsptm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqubhqt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtnqzac.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhwxggi.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmydnqf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2snlhvyaq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cytaslkc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxzloda.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yspcgeij.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eflyknlv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtndpims.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxxzuis.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qejuskvl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2agakxpgv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2navmytes.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpalafts.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmuxewq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwhbitw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpzlzva.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2suvyyqyi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mkosijhc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnpkggk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pleiaubk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpzzzde.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2osxflaae.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdbkyex.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrihvzp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gknybnqp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qigwctuj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzhpjql.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bihzsqyz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbxonzf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mztlhjef.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjmsyyr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sugxjntp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyxyslf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpfddpo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyweafiy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfonrem.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gostcvjk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvhkyoy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxzjcmq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjhrib.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2znbrerxs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzlooat.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhvwsog.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tddnehrx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxgmgxv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaxyexi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nninshel.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2efgtyqtz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcrjvcz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fopbszra.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2samxuwrf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vjywwngc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kippebdv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrteaeh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpqghiv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqfkkye.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2macoljaf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmuklbo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgvossj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvylrep.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgjirxr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xauulrmm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2okguzadk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnddbqa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cequsrdv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtriwxzu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eytddvjz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jahlwqdg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eikvyqel.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsgpobk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgqejro.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvqscwp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrkzmcd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzosepfm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjvgbeb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrusqam.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwiurwl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tadkgsko.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbxfpjt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2killndzz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nutxogzk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiaqsuk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxuiqya.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2stjmwshq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaymfjb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxbfdqn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtysshjk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2poalskbv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oflibfpv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnqhfmu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeogmzap.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwllrmk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqozdwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkuodze.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtosddg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrevvrso.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmlolvs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2eedaautf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2orelkzgc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jftkjfmq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzxkyjq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnvacfe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmkvnyw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iztrxpyu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qopxjqwx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrktifw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnltksf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2snwhnacm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwifaczq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnsqztx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqiqixt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pklbxevy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcfodme.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvxgflb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwdiley.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgepaoc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlojuxm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqlspfc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hasnjwtf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jieiszdw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zworftuz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiujamn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sesljfsb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmjprme.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxklmrjk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wftrwzhb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msmsvmpv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2twdyhwym.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqogqoxg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtwveia.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2araiynzb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxfbkcm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vurhyvnx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysieyrye.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bizltamg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnucmjca.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxuzbwx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnwzidl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wulpotzg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2apsibxdy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxajdbhx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyvugjp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqymtgiq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2teqxuhvh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiovbpg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zebdjzap.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xqspgmty.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axcztniy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vezffcze.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwsxgbb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxlgdpt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iitgrguy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shhdarqr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtkpdxf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2anjysnnt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wygelilu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoxcpeq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yskmbdfg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qaglhecd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdbqfvw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztubievk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjuqrvv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ednllalv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bnusyfqi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2luosryde.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvzreud.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcywvsq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kdabokrq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxndwvh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuprpjy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2okhwgfzo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrqbgfm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdaqnwi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijynowls.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdxgabc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaylcbkk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvfwjjx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuzccng.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxggdsbx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgekanug.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbsftmq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmalmosv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgfcmnv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhvvvcl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gernhrdj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mlndybtk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbrealm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sslafksv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoelemql.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2joetabmg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mltohddn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpvdivm.html


<!-- 参考信息 -->