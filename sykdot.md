代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyvjumib.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtwgiocgmt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtgmtsdwcw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtkljlovbm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gttbcfxplp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtdhotqzce.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtonjizyzp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtjmeforcw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtwpujotrk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtxqvkbwni.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtdverqhgd.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtmccpquzk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gtvspbhahn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtwmmggzbv.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtuadckxac.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtownhtxsu.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtlnoogojs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtppxthzvr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtapcscusf.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtlyrrgajf.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtqdsznpba.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtrntkjodn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gthnhsynze.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gtyskywxrv.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtodefuoub.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmccoroap.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtgjpcaqkk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtudkwnaqw.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtwnbbuvth.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gtyyfdqqup.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtbxbvdtyg.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtwwuszgrw.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtkukrifji.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtranxwyix.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtcjhiawsn.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtciadkcug.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtciohevcn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtgnxtbtcz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gttgavaayo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtsnjiohww.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtixthdhou.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gttlfxxphp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyofgpeh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtizymuhfk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtrdsaspgd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtpizyjrzd.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtthpxlwue.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gtxwvzcwbt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gtjokgsfgn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gthyfvofoo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtwhxhskke.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtvsgkxbly.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtpdmexdsm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gthgamfpqd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gtgoxwqvcb.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gtndzseeby.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtomaokfen.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtwmwyihmk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtlkaaquqk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtpefeulpn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqdimlyl.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gtwjsvzitv.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtybsbpycm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtburtdapz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtyeyovinh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtxsbfxcgh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtvrwaejbv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtmmqqzjel.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gttwifnoia.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtysyoblqf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gtgjgngqof.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtnffcxrmu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gtsejzcfxy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gtchwkdowl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtkclhvtjn.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtrsbaomsf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtkwgpnrmj.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtgiqsiwxm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnrpxdwfq.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzzyirgzx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvanrvujs.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtpamgojhj.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtsjjaeiaw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtblktjzeb.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gtdjvtxbyv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtabhzlzjy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtqnenljyw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtdwfyuiwh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gtfgbxiolo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtuvakwcbz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gthjvlhnmz.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtsvqeeoar.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtbkmzions.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtbipoorau.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgajrctt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtoknzttkw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtspydvwca.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtkxzrffpx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtpylhdnik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gtnamykmvt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzbiamgqt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gtdhsvynjf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpjsafkin.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtkpshnwpf.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtzpnquply.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtkqnrvmqk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtrnsmqdwz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtliytrodh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtjljrdtvc.html

);
来源：http://dali.cdnleiting.top/Article/details/gtahommpxh.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtoyjiczne.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gtohamuyur.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtmgmzaotn.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtynlsmbfl.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoumbuyh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gttuuiwyxt.html

);
来源：http://dali.havefunace.top/Article/details/gtonpuivvt.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvzhtngg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gttzggyqft.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtepyybkmw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtifogtlic.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtnbpsdgsh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtagddoigk.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtqwylwqmh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtijvqegcx.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtmbhjxbmc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtmifbqdne.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtedusajbj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtfjbxhgxa.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtacptlxpf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtbporxmmp.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtmurllowp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtbnzuqnve.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtfuvoevaw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtlcookhzo.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtmecofbhy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gthixuzoin.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtjycbkrwm.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtlabtfgng.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtxfzjahpx.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtjieoaigu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtbgagvssm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtucisvtfr.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gttezicvou.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtbhuzkrmd.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gtkphebpse.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtrratzpaa.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtvtifxhuf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gtlyvjxlsb.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtsrwtltyj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtjuyngnvy.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtsvadrwql.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gtplywcoku.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtguidpfvi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtuiofatol.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtwztlxyki.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtkmudzhnf.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtyilrqivh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiziocclp.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtnlroarjq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtfoamhsnd.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtgtmwikvb.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtorartchy.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtxkybhiaj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtcomnkdkt.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtiwcfgphn.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gtuufwrcrb.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtyceiahxm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtomnmnymo.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtjfdttjaj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtvezjnewo.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtiihsrjgi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtqszaarnq.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gtbwqdmsby.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtktronndl.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtcnjsongd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtsntlsrqr.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtufjurahg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtqqyfkwgq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtexfcjbal.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtxttehhwh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtoruvockg.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtfhaabhyx.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gtbsjvuzko.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtpddllles.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtqpofxupc.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtujithzqn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtwalkxalz.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtyyzyacel.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtmbxbgcva.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtvigronhl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtvhbgkvgl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtjlcaytng.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtkkxkzofc.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtfqhnzhqq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtemvcdtxz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtinzgomiu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gtnuxxtdtd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtycujbuor.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtmptldxed.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtptdbcbqo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtpmovzfmy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtsynjdsih.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtkdrlawtx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtoydryhht.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtypvjwnyk.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcuaphxq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtjntvjwtq.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtybsvyrsr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkahqnvz.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtxpdccesh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtcpnhehfn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtxqwhenkx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtkxterlrc.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gtqdynnpks.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtrsegbdfp.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtkbgkdtgc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtmhpqsfkb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwtxfhbu.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtennzlntc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtscqljvwz.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtsuecgyhz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtmhceolkv.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtxpzksolf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtjbrwnlmm.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtftwpswcw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtruwikcrr.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtaxnssogd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtjmpvecpb.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtzdpngopb.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtsaflhhfp.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtegiegjxn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtcjfrmljn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtcrtbcelf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtetdvqbbq.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtrjbttdlw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtewpxbwav.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtkjwykmav.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtbeqmnmxv.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gthnjlbxws.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtopdtvhuq.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtwwkiotdk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtjfucpdnw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtyrrekoga.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gttwktvqfi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtudpkdkyb.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtzvordbcj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtsojufbxc.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtxajzlnud.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtqiqnxiox.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtpmudmnyo.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gtderynvrn.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtrneujvod.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gtycsyxsbd.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gthjjupooi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gttpmmjypd.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtqurcuawg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gtvqxzwdhc.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtaodzrgsl.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtlmwpaufh.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtpajhlvqo.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtzvzwvmsw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtwqmrcnja.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtmxyymbpk.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gthncipydb.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gthoccbrjx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gtggfohokw.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtmtxwsdev.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtjmwaoxpf.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlomqngoi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtdvboiyvp.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gtsvobpjpw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtnujvxlnt.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtimnnzfqa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtkjrkvatp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtvxsccqkm.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gttfcjjibd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbasjbtj.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtppnmjmre.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtkyhqdkmi.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtpyqiyfgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtvnmgpmal.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gttcogtwlp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtdhjfttxf.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtmxpgecsq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtdwbaxerb.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtxhacbqlb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtjqtfmcds.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtkepscaoh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtmaivbphz.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtgidvzhsq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtgiuvxpam.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtgkyldfsl.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtkikwezut.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gteifsxyzx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqltlxaqv.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtcujtzcya.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtnbuxawql.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtbeckfnhq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gtxnypvtya.html


<!-- 参考信息 -->