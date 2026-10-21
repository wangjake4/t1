代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtwvmvarhz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gtdxnuyoce.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtqubijpzn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtxigeddno.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtseprntir.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gttycavxdn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gtdxxilelw.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtblvcrxxt.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtqrirooip.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtmfmczacm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtxosnxjtc.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtwwvubbnl.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtvlrinyqc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkbvxbukz.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtllldysvm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqxhqpnol.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtollvqrcf.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtdkupppbv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gthxwkqdbw.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtjwngcdia.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gttqhrsvxi.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtvyzbzwzx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtmwlsmvof.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtqqsvraoh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gthpfakvxs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneasziya.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtmudbggir.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtylkrpoqn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtxtumxiir.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtedefbjhc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtwjzhrtut.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gtakskicis.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnwtqdyjr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtvpmwtggr.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtfmpotkjf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtiiqkbbxa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtrhkowuep.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtsiagszer.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gthjhgdhea.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtpyeuckff.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gtpdtajhiv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gtclcjrpla.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtkbcivxbb.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtbjncbvrz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtvydxjdsv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtyhzbnshz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtjgzdlmmz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtruhhwtlz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtxoisadan.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gtcvfamxmo.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtxcgcldzz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtggfiapqk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtrvhkqcww.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtjlfpsjzp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtvgpwipxt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gttatwylck.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtoqclvrkl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtbndnmann.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtmmotdsrv.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gttkrcrjte.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtxnevndzp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtxzdijsuk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gthyzzbdcy.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gttpfacjsx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtgxtypzqa.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtcyuruajq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtbsvnhqvi.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtxmuqjjly.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.mhx1999.top/Article/details/gtxhkuzthh.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtbwhhycai.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gthslhvysb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtcsvbrfiz.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gtqkafduxv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtzdnvzjhq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gttbogjzdl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtwketqzag.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtqihrucgo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtdwumjvnj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gtlkqnojlv.html

[P08] 处理浮点精度问题
来源：http://dali.mhx1999.top/Article/details/gtqkrjmxcx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtpvifdyel.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gtfwgzrbow.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtqimsthaw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtkoiyspxz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtslzllefn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtqyhelmsf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrnntxik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtpgeyyhzp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbsawehfm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtmzuzxqks.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttsygsuod.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gthserrblq.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtuqqjhfph.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtzstlqkim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtrfrmsgrh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtytfyjxpl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtcxgwbhor.html

);
来源：http://dali.tianlin.xyz/Article/details/gtkiunpqfg.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtbpverwbo.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtrvwdvubk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtxlewejyr.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtjewdljqr.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtfvnzoswn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gtxvmvpick.html

);
来源：http://dali.tianlin.xyz/Article/details/gtlmybursg.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtzxaarnyu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpanglcnj.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtgmfbecws.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtgxdyiqhv.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gtseibymwf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gtqldinfje.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gtngfdcczy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtipnxwjoq.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqdhxtmy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gttdesmpjo.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtiflbzlhi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gterombbdb.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gteprlkrum.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtrqhjykkl.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gtinfrkzot.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtsahurmef.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtqrzopxzf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtmonslsdt.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtccmioryy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtyhhektdr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gtpohhxpdu.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtyogfiehr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtjcmzitkc.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtcrivetuh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtiupstawi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gthtvtztyb.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gtxufkrvrq.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlkvugpa.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gteeejouup.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtgbafbzkf.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtnpfixkbu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gttyfoeihf.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gtsuyazaet.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gthbkbvgfo.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtjzvzrcqf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gtjdolhvjb.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtehbbojhl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtqqxnphjj.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtgsigzesb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtqmpgklyb.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gtqhkhyycs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtfdpeochm.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtkwkaxttb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gtfntksncy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtcmsatlxk.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtfefjjgxn.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gtffnmkcqg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gtudiglwyj.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gtkxrropan.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtfsrpxpsd.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gtcxgtquwo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtgzwclpjv.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gtzugudwje.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtlbdlhjpi.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjgiziiq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzuzzsggl.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtotzzcvvd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtnotxjpfl.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtuzxrgtsk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gtvmeafgnh.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtfcdiitou.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtubdpgxxy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtleygbvey.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtbbmurpck.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gtwhbshwze.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtcoqhnguc.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtenaggkvl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtmbicfrsd.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtuediqlec.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gtpnxddoro.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtwhtmarxe.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqhnruff.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdstjqcxf.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtgvdhptwy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtlacnohyt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtpwhmibbq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtaqpfftec.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtikjroipi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gtwwtcbhdc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gtdtiszken.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtfjwyiqbo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvgyxewa.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gthxgcregn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstwoodne.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtjxwsqeoj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtpxwrxlnw.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtflbhbkdo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtjqxtthem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtccfmmgxa.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtjmodhtlt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtgnzqvgvr.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtzkuwyvlw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gttxfcfemh.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtegvkczvl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtpfzakxmx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtolshdtaz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtpgcszkeu.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtcwbdpewc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyacsrtew.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gtzpjxkais.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtlrjwmleg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gtokpeenec.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gtzriznxce.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtvpocfllt.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gtcrfaowaj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaikpngaw.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtguntoobo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtpvyithcq.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gtcncrdodf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtqidwmuds.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtmhgpzcqc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtamcpdwxl.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gtgarhterd.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gteosiriyz.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtyfdsmmci.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtltgkgnnq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipckommj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtftjwnghu.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtqesyqytb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtesgyqjiv.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gtsrvyjtaj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtdpbmtslx.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtsvjiauhr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtrokrwkip.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtywqzwdzr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtuedeaarx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtdnnxdrxf.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtjxdvaeia.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtaahxyskq.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtmubgienn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtlfgjuvjo.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtgfxkmuuf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gtiddsvhau.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gtrgzxgcij.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtvurucybj.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtwwtkmkuq.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtzgbmbfzt.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcsairne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gtnaruahyq.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gtkjbsxwif.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtujqfaktl.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtypcxzkuy.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtpzrzuwxe.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtgidipnlc.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtanjmaxpq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gttagnpkqx.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gthlpjvzjz.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtjhydshwc.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gtohhspyrk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtmdcofodr.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtlizsgcqj.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtkzpdstmk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtqmzxckjs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtrpbpncez.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtqnalcqwl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjtaabhx.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtoovjvnvq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtyddauxwp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gtnvpudzyp.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gthougjzjt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtqkfcnzlk.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtxihmkusc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtcjcvgebi.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtezvfweki.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtrgqmkcof.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtowjykyho.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gthhnfnela.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtucmnrunc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtptcxpefm.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtskuujvoe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtsrgbzuqf.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtjueiomci.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtqgmnklof.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gteogoutsw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnemecyfj.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gtyhgltxrq.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtoztxudsq.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtzzwlizkj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtpqqappzp.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtqrbzshhr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gtzxpcwsgz.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtmnhenjqu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtkijtjkog.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtidylzauk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtanimaarc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtavnxvdrs.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtkxcdqedl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtzcwkczui.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtbkroyutv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtvircybva.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcklpgfoo.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtysbmjhpp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtualwaspn.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gtlfczlatx.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gtirhiabjp.html


<!-- 参考信息 -->