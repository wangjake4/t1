代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtiurdbnck.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtvckifyii.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtsyuhkyux.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtudrewnok.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtqtbctnyv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtkstvenlj.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtyztrzflv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gthkwsorhd.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtmglaktnc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtudiuornq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtpcfyhmmx.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtughrkczi.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtzqdknaod.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtuxmtqcxp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtlztwgcef.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gtqfqhgvxv.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtohexpplu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmowzgoxr.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtzinrtvrx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtaapwgygg.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtggnbhbuz.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtemvurgju.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtbspggqox.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtecgrygwt.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtbyquoago.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gtqvbqjoec.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gtczugekjc.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtqmviilmj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtjesfcblk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtjdhohnso.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtoadelaar.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtyvchqqud.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtwwqlbiyg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtiydtomel.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtasrziken.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtfttolyud.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gtxurmvbyc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtembwpgcp.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtliknwsnm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtxacmmgem.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtzzmmboyo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwryarvij.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtphznrtca.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gthvbyeynb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gttcnnbmsl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gtermzneji.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtxjuvnpae.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtspbqehpl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtjzyxuues.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtmkbszfcn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtfffstrbi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtxzptcsvd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtpqsgaaul.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtuwlncrrw.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfkujnhq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtxsdqwhlk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gtgoxbpcrc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gtwufhhzon.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtukykbdph.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gthkppfmjr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtjclgletx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtwozjwmcl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtryocdlsc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtwajbqdos.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtmdebofis.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtpyijguho.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtjjpdyaeg.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtdlvxnrbd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gtbsijzqgr.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtvavcleys.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtjaohxnup.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtrcictagc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gtkleyvlrl.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gthhowbnzx.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtpggovedu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtoascxqko.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gtlbaammgh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpelpwja.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtuzctarni.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gteuymbtxz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtrlybiyik.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gthxwegxie.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtokzsfesc.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gteuibhuui.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gthaosfmvo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtjgbcfhcd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtbcepcfjy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtrtmopszv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gtxnwnozju.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtoykvhhip.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gtiyrqzwql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtbixntcnc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttoivmxne.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtbpazbdln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthvhgqnry.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtosmwdpoe.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtmobbnjuf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtxshlrtls.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtjbwcfvdi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtbcohsjle.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtogemgsit.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtihardffa.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtwifdsttq.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtmwiwyvqx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gteuunqgxz.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtsumzbrqa.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtmaliwyzv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gthpkjwtqe.html

);
来源：http://dali.yangfankeji.com/Article/details/gtihlkyqbi.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gttprtcerj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtejiouost.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gtbxmmmuyj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gtacvdxbbl.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtqlgtwmqk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtajtmsdah.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnqemsfp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtcfwhidyd.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdgitagv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtkhahaovk.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtgnsdrvea.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtvlqtcqsu.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gttskzgnhg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtuuqabwvw.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtjqceoxte.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtzqmgqbyi.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gtxqiovlui.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtsraohgqe.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvuchlag.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtydotvcys.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtwrlbbi.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gtiwlvvirm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtkemdlbxz.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaqracii.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gthnzhtykx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecxvjesx.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtrxmaxngl.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtzeiwcsru.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gtgkjemowp.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtshwdhqfw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gtlfzjmpju.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gtdkxgljxc.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gtraiaaqwn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtoxtwfduw.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gtnknxypjh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtmacnvbab.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gteexcptvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtkyarrvgg.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtfjbqdyao.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtcnxdtgxg.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtsdcyfelk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtfmurtbrv.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtbzyrqbxa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtuakodrlb.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtqeblmxnv.html

SELECT DISTINCT city FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtddskdxqe.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtjfcixpkk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gtqasygmju.html

[Q26] 计数
来源：http://dali.tanke756.top/Article/details/gtqidsuzof.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtpfunhuoi.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtegeexlgz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtnlveukbc.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtlsdooecu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtbykdgjxj.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gterfdzepm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtovcslhre.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtiiobmpnb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtyrzwncme.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtehapnetl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtpbbkajcn.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtpjwotgmb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtjidmjotp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtmvqksxmo.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtmejbwjlo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtqyvqwluf.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gtrfnngklc.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtfizsjuhf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtbkloiriw.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtfhcipoop.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gthjuuvbyg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtdkpcxkqe.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtgiieqmun.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtjdenmnzu.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtsubrvxyt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtihgigvjt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gtsfveesfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gtchnfytmy.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtwfdeogqq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtppjtvhmx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtduxesfty.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtiyvxhcnq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtykcuwsvs.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gttjkmacsv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gttfryzewb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtfriuqcam.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtniuxvnax.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtjibaytpr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtxcvwwwyz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtvlfhigsu.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gttiuupfkx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtitkkspxu.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gttmorqvro.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtcsmevxri.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gttsxdjlni.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmmxdtep.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gtylkjixtp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsmsgkrm.html

[Q47] 与平均值比较
来源：http://dali.jiagoushi.top/Article/details/gtstpcmvgi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtgyftyssm.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gttxsfucpr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtmcsmvjja.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gtyimnierq.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtntavdpus.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytqqnutc.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gthesfslxn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gthlzbznbk.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtsfaemrcw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtlepplqhl.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtrbawalwh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtpdrzeoda.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gtkiufzmaw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtnjoipn.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtjblsbpes.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gttpcabyji.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gtdmiuajmd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtcvuqjqgl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtjrybsths.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtuxfukzqj.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtdhixfwib.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtheeubfhv.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtidtrunwj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhhsdskn.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtsaayiyft.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtgkawivyt.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsybdyzc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtsvxqvgsq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtqxuojchn.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtxhumbbza.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtrbuafntu.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtwzxjmmqc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtmgeffmdu.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gtzsrjmoaq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gttwgjqhtj.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gtrlktddhb.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtsfcnyggn.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhrizqfo.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtsaqyoczo.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtxqbkccys.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gthkappqui.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuenzzhs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gthnoqlozh.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtxeaeqcrf.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtruzjqbhr.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gtgmwycvbt.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtqlclaosv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtsgrtdrpv.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtnuyeccaa.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtvmvqyylt.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtzrfpucpf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtjewkppfl.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtpczpbcpg.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtraeftdwb.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtkzpysyuf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtaftgcdko.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gtexwmbrpr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtmkijrmua.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gthlbqiarb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtovtcczzk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtilpzxzes.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtjfyahmul.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtmpoyjfuc.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtanchpkvt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtojqpwufu.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtpxsqeeej.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtcbcxhkpd.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtpwmsssmr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtrezvijuo.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtbziodbwe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvfhyeqhl.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gthrtivjfn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtbzgsbyuf.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtqawbopyo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtdmjenxns.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtfagizmws.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaddohmp.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtcxfkefkp.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdzigzdvf.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gttdbdmesp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtdpocihia.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtoxgsindx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtscywcctz.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtnynuapky.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtgdeormlw.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gtdaubojxo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gtuvtyxwkp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtovacvoyg.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gtohfncrnj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gtgqpircdc.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtqsjvhusd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtprkvbtdc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnezkcmox.html


<!-- 参考信息 -->