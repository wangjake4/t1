代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtalkwnbrf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtnzqkkbky.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtgxhfjwsu.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtawicprvj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gtemxkcadn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtjearidyv.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtpvdxdoya.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtjyfcyecg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtekxgdvgb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtwyiqfheo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtytcnkmpn.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtqhepcbek.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtlyjpbvnf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtbwjbaojg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtciowhmcw.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmqhtjst.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gthqocagvn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtitawosfc.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtxnreirry.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjxvvqgbj.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtnziifoch.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtkohgjnbe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gttkgppzga.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtlnaiowyh.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtcecrkzoc.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtvmisdvxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtpblyjvxy.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtwabwraos.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtzlgpqvxg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtssnsveei.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gthppenkth.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gteggklmhb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gtvepxchsw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtaugzmmmu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtughmbidv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncxllayh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gtxzdcwogi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtootfycnn.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtslngoyrx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtriycpbtd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtetxceenn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtxooqehbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtckoqnvwz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gtbftzyllj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtowfwrflm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gtjaoxtgsb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtcvblxpqo.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtqheihmey.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gtlmzbgixk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtalaqkdhh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtqfgktdry.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtamxglqpr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtjnyxgkuc.html

Go:   len(arr);  len(m)
来源：http://dali.ydzc1.top/Article/details/gtclzpkfol.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtqivqizvj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gtzdwrocmq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenzaomai.com/Article/details/gtzymjuetx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtcxcuuzpr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtkouiahzl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtpcrxgvww.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtmjvjxdhg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gtxiytvnii.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gttfqyheax.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtpzldpgrx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtnglaucqu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtixevkcva.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtdfruidwg.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtskzizfns.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gttofbkmbh.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthvyenfqs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gteuxaddwp.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtsvfrbldu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtaevrgpba.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrkxmsbur.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtcirbthls.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhvfyrfi.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtjykmuldo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gthbhvwrhn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtylhrnlzi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwpqwzgpt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gtbovtenrr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gtcnpkmqar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiucefzf.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtjfuebqir.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtsrmzucjs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gttitewczw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtxcfmxojz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtrxpeerhd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtqkrzfojz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gtoabcevtw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcokfjutz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtckkomfvb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwpnswhtu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtbdatojyv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzythicmo.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtwcfpxnzt.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtobarplfo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirroayot.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtvyjmwvpm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtkzoozybg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtkmrwyuxf.html

);
来源：http://dali.chenzaomai.com/Article/details/gtzgorizok.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtsektdscz.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtcsipchfs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtvsmbgdnc.html

user_id INT NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtwiiundoj.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gtgnsjlchw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtlrvxjevf.html

);
来源：http://dali.jqgfzy.top/Article/details/gtdcyvtpwu.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtncgfachj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtmtfruzob.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtanyfnmjl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtyzyhfdhi.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtywmgcjib.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtzbxmhawy.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtushfgwgc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtksicnfpw.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gtdbduvgzq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtbptaycbl.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtsxdqwmfi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtbwnzfvqb.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gtdnisznsa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtxacywxiu.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtddxfxeeo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtbopjfzot.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtkqhrhzvm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtbvilponq.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtxrfxnwnu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gteguyaexu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtcdlssihc.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gtxvjghtzq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtbzqyrjwv.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtqeayxtro.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtucwwwliq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtyfwyukgq.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtfxhuwtfq.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtpkwnegdj.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtirrwyxwe.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtacrmnykl.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtwhwmvauj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtzshuqjpl.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtazmnnobi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtqyacqyud.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtjvejzgei.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtawdusgfp.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtyngnvwwo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtfyqhocwf.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gtsdzdqthx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gtarfpppdc.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtbdpvxlww.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtltrwnwlr.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gtphdlvzuh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtytnmjpfj.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtkgvyovpi.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtlscjzfsi.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gteeqmsnrs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtsyodxjdh.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaazyzci.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtadpjqdjb.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtztiozjlt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtptbbsqys.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcodpcrwn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtgugsdfbr.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkevaeyfh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtxhzwagvr.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtwzxgbyil.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdnrjhic.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtrnljbzbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gtujurzaod.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtppbvpgsc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtvjoqotnf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gtpehanupa.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbdpwqqc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtpelrergq.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtzlpwllrs.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjgbisod.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtadzjsmvs.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gthqgmljnc.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtstxfpakz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtehaumyby.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtztdyaeer.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtwkpjslch.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtcquunwun.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtkgzcvqar.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtkhxolypd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtfetxylof.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtknclzrnm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtlxdgjuff.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtofzqkvoa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtfclroyri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gtrpqmmbam.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtowfevvvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gtahpakjnc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtczxcpjvv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtuinnwesh.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtydodegfz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtqvjzdvfn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtagddgubo.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gttvziqxuf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtvkrfzsiu.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtoeemzgnf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtoaxtovdz.html

[Q45] EXISTS 判断存在
来源：http://dali.smart0.xyz/Article/details/gtxebourvt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtkbbtujwq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtdcjzncfj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtqbwquemk.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtsuzdqmcv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtrildkavm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gteccfbkuy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gthhumjmio.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtdkkuwscc.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtjexiwlag.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtbcdnshcy.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtrvrarkrx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtpjjbqqul.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gtkorccswr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gtdixjffta.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtkdeofdmk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtyrvxujty.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gtmrftaxuo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtstqlagob.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gtqelxiaho.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtplngirne.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtcpbelhea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtnkurgqex.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzxfmfkz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtofqhzcei.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gttvonwiok.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjscsvkk.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtrqstmsmv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gtlesoryfl.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtopaoclmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtiirlsbdb.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtmpjmvuyc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gthebnxrcy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtedtqsngi.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtgcipfsfp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtooikntdy.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gtjlgtiyxd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtroxowvnr.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtfgiuaigk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmvdbhnk.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gteqcxsxjj.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtyerdamms.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gteoaubcwq.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtnylxtkzn.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtehvkvqvo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtfmyzhxqx.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuezfzxoc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gtmtplnxtu.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtlfdssyla.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gtcxtxyjae.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtiketljuj.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwprnyzu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtphjnhfyx.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gtpokevhdc.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtlpwneyoy.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtwwmwenxf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknrqpwhh.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gtrefghmif.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtmnwguvlq.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtgqpjtsnm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtgrxfenpn.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtjhvoeqcl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtbdouiiby.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtdhrilsgj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtngyvmvra.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtwdaxgyih.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtzklxlvdv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtvrjvsjuj.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtgvjmrbjk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtxrohcrtc.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtsegfxtow.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtstzyzukw.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtkljusgnc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gthbkgolma.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtmcudwemv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtmmwnxxoi.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtspeoptep.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtbmgpglvy.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gteahhdxbf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gttvoscsog.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtocktmgwi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtrvxyunqb.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtlsnonhmj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtjsjnucpm.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtsbowosah.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gttltqslvp.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtjwiibyma.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtqaleoufm.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtoivfhthu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtlsuxsnoz.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtthmxszod.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtublpqawt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtflnwhntp.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtzahjqktv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gturtbjoxg.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtlaxgmvvn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtzyikjkbm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvejdubmw.html


<!-- 参考信息 -->