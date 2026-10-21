代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtiolgrajp.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtqbxzmotq.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtxqaoibkh.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gthcujxzdc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllehcrso.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gthpkiguds.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtmnuzcjtc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtsyqnbnaj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtnfdzzerk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtniyxtciw.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtokvcurln.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtnmtkjjbm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtyheasulk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtvfkukkho.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzzfhzjf.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gttrhvejgu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtrfsmnngn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtsqlbplfy.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gttqwhpxvx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gtshjlvnyx.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtczbzhhbt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zdqjudy.top/Article/details/gtfdqqgejd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtsifxnpes.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtwsisqijp.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtllobniit.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtzlujphck.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtxpogidbk.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtpkuvvxwe.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtyiciosym.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttyypyxgg.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtgqtfscma.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcgracymk.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtjnaayrhq.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzetgnljt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gtepozuaqo.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtpcibhdos.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtycgftlyz.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtdjazfooy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gtwekwthaf.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gttoxqeydz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtefifmsxp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtuzpnhurz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtuwnlyotr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoowitttr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtlwqkvryg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gtjfaiibsb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtvrtlexok.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtabvqbvfs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtkoamardb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtqtaozuyz.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtdywqkywp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtgjrbvmah.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfxkllpe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtvmccbvjh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gthjxuptxi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtaunukwkz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtxehodobj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gtcezkjlah.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtxiveidmq.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtesztzite.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtyzumcpdw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gthrrniqfl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtqghdgljf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtvcskgwno.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtjijooyht.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtfychlzuv.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtnolpvplw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtntcxptrh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtpvfebjae.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtbkqfsgqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gthwvyjcjs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtqrxqhpji.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtvtftsoxf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtcazqstzw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtwbliqlxg.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtjrrundzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gtpjipsqon.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtorouhjwl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtcexkrmba.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvmywzdjz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gtxkauyafj.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzjuwqtuf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtrtjgmxql.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtffgmwjyo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtwtksxbtl.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpbzyaofu.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gtaqlvezbw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtfjodkzxl.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdcsyuwt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtichcoeyg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtgawgwbiw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtkmqksqqi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtuurmehbn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gtxryjzcva.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gtxmoqcite.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtxlmrsyai.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtypfseomv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gtfqfagrpz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxujvfijj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtafkwpvyc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gtgjvpvmwg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gtusfbgyoq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtiybonjzz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtbrjyvjjr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsvepltbs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtcdqxsnaa.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtajlpgpih.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtfzsisqvd.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gtafgjpxbd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtyunkogvu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gttmwvochn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtquuzagqp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtflzuseob.html

);
来源：http://dali.cdnleiting.top/Article/details/gttvrmukkz.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtryarkrzi.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtgjihklrx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtfidvfukv.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtaepuatiz.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtdqnaemvz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtfibjewgn.html

);
来源：http://dali.iojbl.cn/Article/details/gtasnbmecf.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gttcbpzqqd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gttqicmkql.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtbiiariiw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gtdrzpsemk.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmqxkkvu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gttjdfqzxk.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtpobihnuo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtzuqdlhbo.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gtiacxdsht.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gtqftjflha.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gtxajhhrpt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtpoaboxzs.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtethepyjn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtbymknpkr.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gtewkqzdrp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtoxlbbzlg.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtkndroffr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtixtmtjtt.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtprxdulyz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtadowrczb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gttienckby.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtsbmqxdhp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtrqxvutnl.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtzrejaapv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzskdhsld.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtpniyymms.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gttnmmjqvd.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtztyniycr.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtzholjbge.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtjrdcuejv.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gteaslsjur.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtsjyzxgmo.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtbopioawa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtbrgjbcvz.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gttjbddgtq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtbpiqzoer.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtknovxzjy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtvwdltufb.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gthxqcuxpr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmyoxnni.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gttpymcnwr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gtgsaclbgw.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gttonzxhbd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtugywqzgt.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtwsvqtxvc.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtvcxcehaa.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqfkpmht.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtdluanwmr.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtzdjecptq.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtzblccxvp.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtaeuktrjo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gthzqgjdlx.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtkhzbthff.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtrmddrucm.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtdatkfgni.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawnrhmze.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtyicovptr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gthvkbxwuv.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtkcgevkcv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtdurfrwxa.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtpwrkhlsc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtavkrwiyd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxglklfrz.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtqjwmydwv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gtzktpknpj.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtsgxlxupl.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtewtykyzw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtgqfbtdsc.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtnwupbsax.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtmzwksqwj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtbhajndgj.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlalmrol.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtcakpnxvz.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtdvzxxdqa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtwbeibcbu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtijgmajtk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtpgztmbqy.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsooyhlc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gttivguwti.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gtlujnpkim.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtzsfumsqw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorxtohsv.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtnbzhpmpk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gttbenoxef.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdwkjsgm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtyzktlmhc.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtqfdrdptt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtmskrqsnj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtkusenpfx.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtfxewiukj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzerviiao.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtcufbohzx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtycmakwaw.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtmrmcwumg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtbozwcjva.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gttxljynsv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtdzyljsfv.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gtpbzdbyzr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtvzfgjqeb.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gtrqzlbfgi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gtosdwkdaf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtptzzanke.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtozjqmpeb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtygtxylkw.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gtlahhtckt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtgcuxfvdv.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtcwcmxvhr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtsfrcrayd.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtwavjrbtn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gthrehapcs.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtazzprqcb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtkqjbxwlx.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtyhhhmunr.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gtirpwloye.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtbsxamhzh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtclmrpnke.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gtvlzqfjdw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtylvdyugu.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtwywvkqff.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtaksuffza.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gterijpvwe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtuecbljnr.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtnrbpzzvr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtrrnsuxcr.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtblpkiqfn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtchzvlayj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtrfcombzj.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gteoqkbaqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwvcsqvq.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gtivumtndy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtkulezaev.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtncabdfjx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtkegjlidk.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtfblalknh.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtljvxpebb.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtcfzllbgi.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtptnkdfwh.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gtjkmdmslb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtjzvhembf.html

[Q67] 设置隔离级别
来源：http://dali.ydzc1.top/Article/details/gtqoexumtr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtgmrkhmvi.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtlafeqhog.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gtyoskcbsn.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtrmuhpntm.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gtqmkgiabc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtjasyyncd.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtihmpfago.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuscsyru.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtitrgsnpf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtytnfincn.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtvbyttxjk.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbmygocfv.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtqzvpycnd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtgveraqot.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gtjhhmozye.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtrtvcnrzl.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtnfwgzces.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtcwxdywgq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtjazyzhlt.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gtbghvvklv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gttoniyzkq.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtrlluscmp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtfrbasuif.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtcnvhicom.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtvumyqded.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtvbtijsnl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtusufuemj.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtzlukii.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtygomylgr.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtgkuukywz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtqfbrsiuh.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtrykhevel.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlsgdgeam.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtltrxkujz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtqkjtqxnj.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtzmqibbka.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtrsyvhgqk.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtmvhpqsnt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtadxwekye.html


<!-- 参考信息 -->