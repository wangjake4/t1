代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtmtnbukem.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtkhalfdjw.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtgeynmdrt.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtrzykfudh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gteywgpnsb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gttojwwztb.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtwzreluud.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtdiifjiba.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtpthkpwrj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtwmoymvbf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtxltvtrqq.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtheuejvjh.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtehpwksbc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gthwyfdmmf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtnrpelyif.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtdhkmdcxy.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtiaqeisiy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnzigkqwu.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtwdqqiyyt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtidpwbisy.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gttmusblve.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtcxbpawle.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtgyxhylhk.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtlbobhpvj.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtoxcbdvyt.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gttryvxeax.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtngxyendz.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhbgbkbg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtefwewxga.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gtxkzqfdrp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtnoiabgca.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gtudjdubwi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gthzhsfjjx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtjwomiueq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtjotrevar.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gtmiiwcmlj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtrfsmupne.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtzlerkhlf.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtvrltlnpb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtalrysdtx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtfsxifwph.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmzwbztx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtxxvcxjnl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtteyxvbzm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtnmecbfnr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gthuvzbklz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gtqlordmnt.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gthshgcjor.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gtnjwxfbmw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtwuulgqon.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtgjbhehlj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtwokspcqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtqszubotq.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gtlnqkttha.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtaswjoxzd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtzdzramui.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gtebhotpnb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gthqbmwevc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtsqnftyfs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtabizoidl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtohqisoac.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtjhrwpjuu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gtzkfkbkfl.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtqgdpykqc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtkaigqono.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtqbqspotx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtmuyvqmst.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gthznkikqu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtwwwihydl.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtzxkkbbig.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtuetiaqmy.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gtduelksyu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtwysolcon.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtljlnmrhy.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gtoqtmgqlg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gtidzecrrn.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtjodsqadl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtfumyekov.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtzaljhdrz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtgdqkbswv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtvqnwoksd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtibyefunw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtnsuacare.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtgnfjdsau.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gteezmraai.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gtlaczyfkn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtjengkmjs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtfgoaxxwq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gtyctrlcsm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtzloulmay.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtzjtciffd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtyiocepuy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzcnkrbha.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtctsqpdhb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtypmscqjr.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtxcncizub.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtsurrqupq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtujrrhqcw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtkpcwxiyf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gthhjiqigh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtuqqgvvdz.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlayyhdb.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtrpuaofjk.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtgbahdgpe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtmmcgjdyu.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtzizdhwqx.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtygkuklmd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtnhdroiol.html

);
来源：http://dali.c1oappe.top/Article/details/gtomfbxlug.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gthcepmnte.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gttahmteux.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtvedqunrx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtynghkgqy.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gtkgzjhbmw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtodlvvrmi.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gthdjyvldn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtkmwvqcnn.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtccbetpgj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtvlcflqrx.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gttjydzerc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtuohhkqoa.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtupvulkii.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtkeqlerka.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtqfnmxhjg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtyxagsajx.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gtwcpjsbom.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtxtxbcqap.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gtblkdqluu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gtoaaolqqv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gtkoazlppi.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtvdypqdib.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gtelfhpjcz.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtcgyrmtbv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gtiryuqirg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gtpbjpdoxw.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gtfyblsgdk.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtpptwulqc.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtduzxrcbf.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqaugyoay.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtksdnzgtt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtpdmndyeq.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtvaqzgxar.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gthxtjpalq.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtsybyanmh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtajtxqtlv.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtomsidcpz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdkpzdvl.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtqluhfpdm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtxqzevlil.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtmpanoadc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtnomzjdns.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gthzffasdi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtyfwdlyhf.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtvmpmogvd.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtabkurjaw.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gtuhlrycpw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtaiijzbob.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtelmzhqcy.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtojhqdswb.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtyodubdtr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmervozrk.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtdircxecq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtnbkqgnhu.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtlpawepjh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtljwbfwbi.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtasoxcxks.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtphaqacte.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtrpkaykkb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtcjuumneh.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtsbhyderk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtmeripjty.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtoqngztnb.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtpszwkyjj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtwyycfrqw.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gttdjhawpn.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtoouojhkl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gtreekkrzh.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtijeggcaa.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtiuwmteby.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtczpyaugs.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtestrzzay.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtyjqtvfmq.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtkcjxksxn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtxcqhpefp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtzfbwnmck.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtofnxwzhz.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtroxcggii.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gtleqbyuxw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtpgviwcbt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgfmjdwk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gthpsrxwez.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtemrxzpfq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gtesdthrha.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtscelzhfd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtmuaablpe.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtmjaxrrcv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gthallcfpk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gtoxmeksee.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtipyocerw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtykzmmqrf.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtxhatlcuv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gtyeugxrat.html

[Q45] EXISTS 判断存在
来源：http://dali.shangyingyoupin.top/Article/details/gtnytbzpad.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtqoqydgjr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gtwtwpkiaf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtgkrzsnog.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtdbxteyfo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtzskwmbwb.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtbzmkgkxw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtpchvggdy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtytllwunw.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gtovvtyeif.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtgvmefvxb.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtwtmmiyfs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtzzvcswou.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gteakmcdlt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtwopuuoaw.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gtmbdkvfgh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtyowfibzi.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclfwkmin.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtxxrmkqls.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtqhbfksvr.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtsddleepx.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtndxqxlua.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gthpypmjjq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtvbktxdnz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtwjsseszo.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtqseiwsdj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gthyhzmwpa.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtntcqqbnt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtzgmkutvm.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gteomzvofv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrseixnz.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtgyluvuru.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtwogbcmzv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtiswfkqfm.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gtrkxnpgox.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtkwkioawe.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtfiqjkkfi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtmhoyykda.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtohnzefxa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtevpqxbaa.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gthzotkyfp.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gtqxjvlqbl.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtzoactdbn.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtjuzbnyrn.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluiwydow.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gtvmwkloqy.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtzokwblkz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtogrkpdfh.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtdwzwjugo.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gtzxwnysen.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtbpuoqpdt.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtnzfdprva.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtdxucgdvb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtwptybxgy.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtxpdcgzru.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtqadrzwep.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtoprqrwsh.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtkquruuzf.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtahnqbtwt.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgiwwnmk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtgwonlfkz.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtvhagkncj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtziztjvvp.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gthborfngo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gthreqiogk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtrorukdsq.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtyicrqsom.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtdguzfodh.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtwbcxevst.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtwzbekvha.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtrlrjscfm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxrtbqnq.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtnyyidmtf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtmjcbqzgo.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtchssykbu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtfrdctate.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtndwnitvl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtotjlrwrm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtegwzwqdw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtnmievpzt.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgbgjrht.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmknezuzv.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gtinpaofld.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtndzvkkou.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtjtjrmtse.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtsvwwppfi.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gtdrcoupqx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtghpvmers.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gtcrbworsg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrirvjuyk.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtzbjldacd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtxfprdzld.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtrirnfjsp.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtictuzllh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gtzagzvbox.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gttxrkvvqo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtlzxmesuj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggnrpsoi.html


<!-- 参考信息 -->