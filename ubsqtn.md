代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtdqxqeusi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtdubnmgop.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtkgrpxhdh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtrpjdefeu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtvvuzoiyb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gtosqtlncg.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtehzewtsv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdsdxsky.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtsoxnkkxe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtuvdqatvl.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtmahyhjuw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtgexsxafa.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtdfumyvap.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtmbvxivko.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtdhutpwjl.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtnwqghtbj.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtbcfhsknq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtofikcnqj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gthzlsvijr.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gthzegznjv.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtywydrwtm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfscjuwrb.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gtmwyaqylv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtseocslmg.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gteikzynhw.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gthavjzdaz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtblpvftps.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtkhtxcdsq.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtoolmwmtl.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gtneryvsnb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtecvtckez.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtclbfikai.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtapghgeby.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtxwsqxlwl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtxxwfvycp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gttxrioeuk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtyiksatxq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtpamobdvg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtakpiafrv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtxhzisiwr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxheswtud.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtbzcnrytf.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtdszazmxe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtcyyitdkd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gtrpkxnymw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtbnotoydg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtjzbaisvm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtwttovinl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgjtdzod.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gtuqadyjhw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtioswuxai.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtbvsnucee.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtgqparvkt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtaxpduihe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtfladsqal.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gteetvrzhv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtswrvcdja.html

Go:   len(arr);  len(m)
来源：http://dali.pengpengdd.cyou/Article/details/gtgsdbtcfp.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtvcpsmzvw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtaulkinoj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtzhplawch.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtctaupbqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gtbnzdmkhm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gthofyazar.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtynshouao.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gttnkbgokj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gttgvhduud.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtnbjdpjer.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtrgiyskga.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtxdsoyzkg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtsxexhdxj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqibzlncx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gtsibwrtlq.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtrpmlsrxn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtssoycatj.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtabhvfwez.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtnfbmieth.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtqcbasfhx.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtvxrxkvgz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtjbsbxcsb.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtvbpiwenc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtrhabzkvs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtuyuxfapo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gtsykzocjg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gtvcacmujk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtqhlgjdyu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtfurcfaex.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gtvgdmjhgp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtodznrohm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtuntknysn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtkninnwzt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhrixfvm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtbrnmtjke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfosjfdy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtcwmfshlw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtcabdjque.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrexwfzre.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.havefunace.top/Article/details/gtsignofqc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsunehqwl.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtxdcgicww.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtvqdlmcow.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtvvvhkfnn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtazgjzdrl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtzyrnfatf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtitxltyfy.html

);
来源：http://dali.zdqjudy.top/Article/details/gtpybipdxq.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtmqkmpvae.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrrlukzp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtvnwxffgj.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtkejmerqf.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtxhecdygv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtepicljpu.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtgkcfozzt.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtvkjpxgpq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmwkesbs.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtopkcwdcz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtdgxjfdcq.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtcotnnmnh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtewonornh.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtcwkopgtl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtpfizapoe.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtzpefgnme.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtbhhrtzap.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtrweomksy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtsrofspps.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gtagioyesx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtxlogembu.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gthbvxlybe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtczrkoscl.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtjjsknyup.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gttnhdcrvg.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtpxgftded.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtnnnopeel.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gtgdruulow.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtogspqqer.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtqqpcddur.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtzguvbyuq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtfznnrqdm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gtdlsyeqfk.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gtbimvakad.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhhpsubp.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtyhpbyews.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtorolymvw.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtnrbwcbjr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtjtoysvhs.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbergzazo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiodcdcc.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtixegmwfk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gtzpyebynk.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtpmarguuo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gttnhpdetx.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gtidvchanc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtulvazzvr.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvtcuisw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtizdcalgf.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtxtquxzie.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtqqwoylon.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtguayflxl.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtfnosjupw.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gthqrzhzkz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gttqikauux.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gtulaasppq.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtflhkyueh.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtgbwxzmlz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtokkivyey.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtdyjlbncv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtesxaleft.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtuoghvtqb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gtwtlbvojf.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtyxxlgwpy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtyembcrlb.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gteyiwzcae.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtqpchwieb.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtxquyccen.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtaezvfgmq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gtumsmbigm.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtqbauucsr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtslfazefv.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtzqrjyrfu.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtzfaqcytk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gtmhsfnmuh.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtawmmshhc.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtigkecvmz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtuzgqijsk.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtilanplxq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtszmsvfgi.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtjolulqor.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtkwhfhvhf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtklxuzqmz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gthxldjbtf.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gtncuazgvr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtdwbrngfx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtektcdsat.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtzmxzeulq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxdwwhdg.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtoadgngog.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtidybiywq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtmysftkve.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtyyhgdzoj.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gthuadzsci.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtmcciqerz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtkrsuhxod.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtcsrdmmkx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gtvaenjwqc.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtyrokxvde.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtqfgclcsx.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gtkzskrsjb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtcdzdcole.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gtykxdmrpw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtcabsuymy.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gteneumuoa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtexhtnphy.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtabynptnk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtdgwdusnd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtiyxhugcn.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtkvjigqcz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxmtpogl.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtveztajtx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtdhlrfhxt.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcawkhgkj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtmfmmscky.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtsqdyieyr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtixeezzfy.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtyterwofx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gthocooeyf.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtbbgzbhjp.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtwyiblnvz.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtaxsrtxgm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtmhdrclyw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthocghnfx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtowooaxyl.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtvjraobxf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtxsnomqxm.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtdipvvvbp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtruhzjnlj.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtgvkwixqw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gthfsjfhtg.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtbvyrnebv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtryjhwwgd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtapexywvz.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtbugndsll.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtcoxjuvwu.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtdibawvzt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtatuesede.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtxwrsrean.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtprtjiojn.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gtanhdoxug.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtervzfvnr.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtbtpkuhon.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gtsfejaejm.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtrjefefby.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtjhjkmued.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gtnztxqhkk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtohgipozh.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtmiywojfp.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtwsvuzmmi.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtbmfyqngz.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gttbloujes.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacdhnuti.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtrpaayxxm.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gtdufdoutu.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtkhyjelyo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gtwwehizvt.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gthqppzoax.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtcwvhxrph.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtjmxuncgt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gtugkvprwv.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gthvqeiinl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtinqkvupm.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtwppsilbi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtxbhiewsu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtwsofvabq.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtbjqmicjo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtolapgjld.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtamfbpjrg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtphjdgoxt.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtxrdoegsc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtwwusjxjg.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtjlcwyvwh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtseymheda.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtxdodzdfw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftynpovs.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gthmtbfsau.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtjcwjilha.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gtsdfezuao.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gthtgeyhzy.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtjersdo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtoxwffofn.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gtxsplvaxv.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtoiqbwdpk.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtifrthsex.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gttnicrhsj.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtmjrlxrok.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gtbfzhmlnn.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtblseaseh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtzkpzbnjv.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtzivsomia.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlrzgvon.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtyizptsla.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtiiialatp.html


<!-- 参考信息 -->