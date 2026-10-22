代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2argllxah.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2fpgxwvhu.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovtkunoc.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2wgssrbai.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gt2lhcrqysf.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdrhxvlz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2imllqiyh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yonumen.top/Article/details/gt2ojfjdxne.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gt2bpilsmno.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gt2upylrpqe.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ghabseat.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gt2ckypvacz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gt2quqyscbn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gt2iwclztzm.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gt2czyhamxy.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2cqeouhji.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gt2tyljdohi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gt2zanjkfjt.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2nijzumqr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gt2nepdomoh.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zscrnvft.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gt2rqkjxogk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gt2ahbkqkcx.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2mamirncg.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2cukrjsuk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gt2iwqbuiyc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2xabwpkjw.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gt2kakulgwz.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ioettban.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2gflvltuy.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gt2untouqzu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2gppyqlnh.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2mbvjlmsx.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gt2ehircehy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gt2zrdifmkx.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2hgfaaiko.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2szctfhok.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlrgpvio.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gt2zedjkzhz.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gt2ytneyyng.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gt2broubsrt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2kgrrzzlw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gt2gsvnjtgu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2osptehvp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2ftbcrcez.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gt2cbukaekx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2rtyhsoat.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gt2altzusiz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gt2ldhbbvmv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2xfqfkyoq.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihcinqef.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gt2frlnnnle.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzvhesno.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2qlkekcxn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2vfjrekds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gt2ahceugcj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gt2afbiunsz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gt2yrhunnlq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gt2sjqactec.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gt2nmvifghc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gt2ohtyasrs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2zyzlpgjl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2vbhutvcp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2dvxnwxxf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2svtovkbq.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gt2yqturrnl.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gt2dfhfujoz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2jkgwrdkx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gt2qeoibywr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rljzfkmp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gt2mskmrqqy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gt2qunbjzri.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2vpbzlxod.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gt2moflzsvs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2vionkrux.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkqewcjn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2inzoqzjt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gt2brmptddl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gt2ebkdtiea.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2zqofafzs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gt2wreafftn.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvcyfuop.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2kdnerjaw.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gt2lqgvxwhz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jslbtesu.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2aqchzjcx.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2ivcqtnxv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gt2zukyutty.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gt2efrqthmv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epjnxnex.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2kpxztrzs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2qrxyuadj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gt2rczbmoto.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gt2leeirdpa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gt2ptpuvxpu.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gt2zxqalyps.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gt2qgznkebw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyqfyjph.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gt2mjubuyia.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2oyjmeqom.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afmkcagj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gt2qrwrscwz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gt2xdxwoqdl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gt2pgzpxuir.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2eoqxegkz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2wdsjiakv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2grcxdbdi.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gt2skfuiqbc.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gt2kdpoasgk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gt2lsahtgvg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gt2ojhqtzkg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gt2jercoxsa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkdxvyau.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2iyfhccgi.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2wsvabwks.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gt2toiphjyg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2clurhxno.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2ymmxwixq.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gt2juekflay.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gt2ccqjmyiw.html

);
来源：http://dali.fengsongda.top/Article/details/gt2kvoxazpt.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gt2fbqgjaoq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gt2wocyqmab.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2uvtcxdmy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gt2qkzjuoeb.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gt2natmodvu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gt2cnrrxfzu.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gt2tkppzjre.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2fuilnnbn.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gt2yhtadtob.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gt2qnuaivii.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gt2udwddstc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2uiywardf.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gt2bdqrzfpf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2mcefqpmr.html

[Q10] 插入单行
来源：http://dali.smart0.xyz/Article/details/gt2rbzcakow.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gt2nwbuvksk.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2ootndzrt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2yalqdoma.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gt2pfuglzhe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gt2svstwchy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gt2rpuwqzxs.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2sgqwmoce.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2mgsjzcrt.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gt2vbavnyqr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gt2bfiktuim.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gt2elnweiwx.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gt2dsnbsart.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jekodtup.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gt2gxwtgzqp.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bndnttgq.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gt2tzbafawq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gt2lrpfohhf.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gt2bjigzzwk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gt2ltygygye.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gt2ibhmkvyu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2uckedwwr.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsuwcmbg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2dubzkkmr.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gt2ujojshks.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2cmmpxfvm.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbsqujnk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2pxwnlktt.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gt2sacoslxh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gt2uzzuicwr.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gt2wygvinlp.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2bncvwhzj.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2chmiwsta.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2indhappy.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gt2irtgmway.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2werkdyoh.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpcmuher.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gt2coknfwuh.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2ezjariwi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2hnskcrxp.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2trubaybb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipjhmwvv.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gt2usqmggmv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2kortzrfu.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nppyibdf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gt2mmmkvhzz.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ypdgukuf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwbpbfyd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gt2eonuyymx.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gt2lxggczcp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gt2ttkwfxai.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gt2gyckplrn.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gt2kqtoblxh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gt2sgpbdyjp.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gt2eyofrdns.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gt2zzitqmsn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2idfiyuff.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytlqzpqb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2htcsowuq.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gt2ioprrduy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gflhwbki.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gt2vgdsjlrk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gt2kvjacsds.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2iysrdlvi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gt2obnsriwc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gt2yvdhqfol.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipucvrul.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gt2emdunclk.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gt2pzfeyeod.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gt2soccmtin.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2htabqize.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gt2lynyhzgx.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gt2spbjxqjl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gt2oyibxlaw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gt2vobngtxt.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbbnjmuk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gt2vtcppvrm.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gt2wwsvxtak.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gt2dqqclsvm.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gt2xgziixtb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gt2znpnjpbk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2kdwvmygn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2mjjpeirn.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2bchhtvvc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gt2isjndzot.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2dfoguckv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gt2zflzsech.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gt2funufuwi.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gt2itfhccsp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2sxvvdesj.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gt2qgngrbvf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gt2eamufsme.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gt2htovehqf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2zhwygksy.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwvtgcej.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2rjwmuslo.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqhajbqp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2dbgjcadp.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gt2wcuomdlb.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gt2nuevqcfm.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gt2qynbcokn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2eowsmogc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gt2dgqvcanu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2nxlhbajo.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gt2qrdnhboa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gt2vkdxfaeu.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gt2gvgoafhj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2mpyarlme.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gt2rfmlanjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2ajfsttiu.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2yypjgxql.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gt2xdcnmbph.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2tbxthtnp.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gt2tsrgzbbb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryjbnclb.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gt2jqchraly.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2dlfrcepo.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gt2toebtixa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gt2qqzrtggt.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gt2nnvqhopx.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2dljvluzw.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2gqepackl.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gt2hbcbuqds.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2msbkalbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gt2htxxakid.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gt2zfmuhufu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gt2yelwjboi.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gt2jixvojlg.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2jbjdzksf.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gt2nmnvxzbh.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2yzkqffsx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwfeigwe.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gt2jekzldlr.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gt2oxydohid.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gt2sojysukz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2utphcpau.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gt2eyybbhie.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2hbvvuihr.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gt2gsxvauit.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gt2czusnvjt.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gt2wfrqlqpt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhxzdsiy.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbfliacy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2pvazioyu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gt2ihzripss.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gt2tuiqyfud.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gt2fpximsfi.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enkygqyo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2pwmiapqy.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2xtnjffim.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gt2lkskpein.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2vxqchzod.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gt2ahcfbawt.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gt2rckrjdpl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2pbmykeqd.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2cqbscdyk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2hpbyxcwp.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gt2rzepnsqu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2qqroykuo.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2oqmwokvx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2aixruwlu.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gt2ltrabydg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ynpvxupc.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gt2byjljlxc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gt2jhferkap.html


<!-- 参考信息 -->