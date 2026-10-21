代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtwnxzcfsy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gttkchzxkt.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuahoargi.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtkrymidxz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtmzbgqjps.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gtmctsrcgn.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtdspchccd.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtihftvsex.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtmmhxqmdb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtmhfkyudx.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtaurlgycw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtooqdslkp.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtspqtfbpt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gtmxeplxjc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtbknlhswm.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gttxrlbbzb.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtvsaapajg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtrdippgsl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtatuxnkxm.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtlsgsoykh.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gthuubjrdf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrmnvoayv.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtbcjewati.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgejgsgzv.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtfcvdnbtl.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtvzzapudw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtkymyoajz.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtwkmikiph.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtqalybkoh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtwzksmnfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gthxafwsvu.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gthiwkkcqz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtfhhscxcz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gtichhuuyn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gtrrjhmnvb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gttuhxuoqx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtppswfpzs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtojsyxmsp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtxryilyep.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtneubmeul.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gtrsrzzcpt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtsjnwpfie.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtqqfpuucv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtdooivjll.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtirmjdnuu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtytqkdana.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtkuqsidln.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtiowhjsdh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtwqfmlbpi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtsrbuhjal.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnughknov.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnjodqck.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gteopqpptu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtpoqqybzy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtgofrgdom.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtmctmafer.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtxekponsr.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtdlthrrxb.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtjyabwwhh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtuaapaqci.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtjquwevse.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtbguxcpve.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmmdkraj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtkuumcodm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpniebvx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtbudrhqhz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtxnodqvfu.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtkkzueova.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.birdmap.top/Article/details/gtzfldrtjm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtocxozhhi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gttfzjrrph.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gtoefjzbso.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtgowmquxe.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaptpkvo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtoxobhmyo.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gtkvldmznh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gtzsvuacly.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtefffpxii.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtnezivxhj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtzhhgeyfi.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxleklba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsjsnrzs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtwqfdqamn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtbtvhaebj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtprcitirn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtnakmboxp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gttfsupvek.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtksnxmebs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtoyvsduqj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgznjsgki.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gtagjavxpx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtdzamulra.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtylinalwl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gtcybcxkqu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtvmnaftwu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gtswcsiapn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmrtwxvqd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtjhvwpjph.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmfbyrgyv.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gtntpzaqyo.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtxohjhmfh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gttzhmnpgq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtrvxnvkvz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtlvmjwokq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtdrfrdffb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtjlkvrznd.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gthwdltgco.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtregjiwor.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtibqjfzmi.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtvahegbps.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyngyssk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtkxhbjjoo.html

);
来源：http://dali.yueranfly.top/Article/details/gtwptheiii.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtgnmdneju.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtmqpxecrw.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtulfqgmhm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gtkqwnbkag.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gttrpzsfln.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gtgulxzwag.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gtkueulpae.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtmnxlfkrn.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtfsmykxmi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gthafhkajv.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtmupvrwyb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtdxpsexfc.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gtjyougdiz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtqnpitsou.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtxrbeyedn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtyrjmsnry.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtyvbcdzwl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtubjzgguw.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtmqhtabln.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtonnzcimg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtdzoborvt.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtgttryzql.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtayqnpkwg.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gtxmadnnqh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gttbzlwgbd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtksghfdkg.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtbbacadlg.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtjxqxhnii.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtdznpylzq.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtmxdlivvv.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtfdwjcmgl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtjxeudxhw.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtjlyndtpz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtpbnryvqn.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gteczapghf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gtatvfefwt.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtmjplcirg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtlncvosdu.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtmpogjadd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtdfpirzfi.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gttyxvzkxi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtxignutku.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtlvkehxjh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtnywhfbhe.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gtetgqbxts.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtgvstymrc.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gttyttukgw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtjhendcxv.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipitsils.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtmakfgdtv.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtuhzqiysn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtwbdkndry.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtjmmxmdsy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtqcjydwnt.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtoihxbivp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpuucbld.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gthtijwbrm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtfcogabye.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gtqvsjerzg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtenmwsdkx.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtaxzodljo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtaigviynx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtpoivahfs.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtzbznfdlb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtkjdwhrky.html

[Q34] 每组取第一条
来源：http://dali.hongshengwenyu.top/Article/details/gtwzmdchfk.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtccigloug.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gtfjpcfuin.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtbrfuagir.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtrppqusas.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbmdccdb.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtritzlxgw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtrbowmjsf.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtvtwqqzkx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtsetkpmww.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gttspxjdwb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtnnltlgwm.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbsytzqk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtodctjufj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gtkhpqswqx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gtjuuqdiwp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gtghvjrpti.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtcgjxubct.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtxzauqpuk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtmspnxjbk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gtrskpkzpv.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gtmgnqngys.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtlkshauyn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtabflqeie.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtyjfowhlk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gttycgyfup.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtigxdfwam.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtklqixudk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtmkkcubqf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtfqbjlonq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtrhzvecdi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gthyjxwdqu.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gtekbvuogw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtdlguugid.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtpejgetzc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtqbnscbwm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaopyjlj.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtzbgwhdvs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrbkrcfv.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtfmceftin.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtrfppfgzw.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwlzbfcn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcunesvbo.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtmcizbelo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtylzuuadd.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtdzqoafbw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gthhntzdhc.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gtdqsnnulh.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtcyivqwvc.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtzpyatnkv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtzgdlbtki.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtwsuailkq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtnjaesrkn.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gtssmskobt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hammf.cn/Article/details/gtjcvinxuh.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gtnezqquga.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtujaveris.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtgmsyryzm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtyoommwiu.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtrsvihjph.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtszopzzuv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtkrbziqsr.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtlzgqcyot.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtlmwlqapq.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gtudqutxlt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtzvylzakm.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtmlytfzgt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtsnaxipna.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gtwhktdesk.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gtqvdtoafm.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtwpqtkuzn.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtjtniuaqu.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmcmsyvi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtunyzkwdw.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtbguvqhqk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtgzclpami.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtiqxfwcjp.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gtlsapmhpy.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtelegmhkw.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtccxxvang.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtkykzvjds.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtzgbgtigf.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtbhnxsroe.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtjlctmxqu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtcpkryupg.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gtonszclqv.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtuiqjhrpo.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtapgguhku.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtgcgqavoh.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtauuboqxd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gttniijsqf.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtogxspogg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtrkrewfqp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtmlibzxfp.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gtulfqxlva.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtgoimbwyz.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtsxrasxti.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtqpoyvqbo.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtauikjwnk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtckolvykv.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtqncyhnsl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtxumnhouw.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtsvmvxnlc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvlipjff.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtjhvnlsky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gttseofirx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqjvfnkq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtqxhzzeqa.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtrypoobxt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtwclvxcyf.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtoyyepuya.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtakzlchyq.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gtmgwafiwm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gtdbknfryl.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbtaiyci.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtcxjlllry.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtgsxyivvq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtmylxkpkn.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtnwaegtev.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtbfhxwmsj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtpxnpzjob.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtwaoaytmv.html


<!-- 参考信息 -->