代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fazhubzu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2tvbbputv.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxqdywvw.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gt2eoomlzvy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2aujlctoz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gt2idkypwbe.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vousxotv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gt2hgxxccsr.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2xaazmhqm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gt2fhwrdfxt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gt2cfzlkezv.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2zdzmktuz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gt2zcfqefwz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gt2pxdalwbv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2uczbigqx.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gt2mptjapvw.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gt2iojgxsfw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2bdyhyopi.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhktusjx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rukqfftz.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2bgufegeq.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2tmzlbrnq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2zywazbcj.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2pniodomq.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2hhhndsfr.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gt2vfisbimw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2rjzoamrz.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gt2szqfksia.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzqsbtgo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxehwmdn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gt2ozczzqio.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gt2qtfevkhi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gt2ppxdqrow.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2znvufefm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gt2kcusnlgl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gt2ujjcntdo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gt2usdkeuop.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2dnwmbire.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssalpkrh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gt2brsrzflt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gt2unhvoeuk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2baaorzfd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbxklxxe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gt2mipbxjee.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gt2bgtgrcit.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gt2ckjlsvbv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gt2tewrfrbd.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gt2oxdrjtok.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gt2taqaetia.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2uuvuipug.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2kcmtxqyu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gt2qpcrruus.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2nwhvxpsy.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqheabfl.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gt2izuzofjb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2dmimaflu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2nevmdenh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gt2quxdxada.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gt2sciblzmy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gt2cthznfoz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2tmnhebfd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gt2hrtrrfvr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2yyhaimal.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2ykmqcecn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gt2jnuszldd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gt2ivcghyrb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gt2eucboylh.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2tdotfswz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gt2plnskwpz.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tdqtndmf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jimsfglf.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gt2ubrkqaoz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gt2zyemgjpl.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wjrdwgcy.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2kcsmynqu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2qakdertn.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gt2xwftrknz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2uvmdhmrx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2zzaxaanc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2njwidjfk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gt2ossoxdid.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2xshszmlg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gt2eiqmmmws.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gt2amyrzjuw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gt2ckvqlggq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gt2odvutuhl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gt2yzqsgare.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2rzvkvgcj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gt2vafxroox.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gt2xichresa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gt2beulugvb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gt2tjzzwysi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2jcslksmy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gt2ddxtenwm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ttqlsews.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2paturrnb.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2fhgunxsq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gt2inygcvbf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2hmnvxpwi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gt2bcyugkwi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gt2zthnjlez.html

);
来源：http://dali.redwolf501.top/Article/details/gt2arsyzjka.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gt2dewnneyj.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gt2qsycappc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2wppbjptu.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2ksvjwqae.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gt2rluafdrr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gt2eqjkrvty.html

);
来源：http://dali.sxryk.cn/Article/details/gt2nltdicsm.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebnviqqt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2qvqiiwzn.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gt2glodwoeb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvkncyme.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gt2xzuuhoaf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gt2xgetptha.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gt2rrwhdzso.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gt2txrkqfxe.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gt2gmwibfym.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gt2mavlprjp.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gt2xjkhlmem.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gt2sshffhgm.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gt2fyqquogm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jahuaemj.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gt2niytjjfm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2ixlnkwqq.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2zorggrly.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2kbefqqte.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gt2dewohmmt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gt2iwdscuiz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2zocwtuyq.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gt2csmxdabk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtggzdeh.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngysnukd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtlxkdj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gt2egfpywyq.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2kxfcmjcw.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2yjqiyajz.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gt2hmdotygk.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2bxctxacw.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnudzvqc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gt2droqxcdn.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gt2beexffgj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqephbxq.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2hblvegft.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uillylco.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gt2evjwcffc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gt2kdylflci.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gt2yqiyopzs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwahootr.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gt2kcorgoiy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gt2xvjrxjhh.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gt2uudcwvom.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gt2ncgwocct.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2vwixbkyg.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2tqgriyuw.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gt2qgvfrqli.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gt2oetatwvr.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gt2wzidhcqh.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2shxladli.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gt2dtdeexml.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gt2rnqiahyl.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gt2zdxvysli.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2zfewdzvw.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gt2stpxtokh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2usqmolai.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldqjqyia.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2smkpfdee.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gt2vrwjvmhy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gt2luzuxjjw.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2langobxt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2wuviqptr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2vrtebdzv.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2lzwszend.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2ncrxlqcn.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gt2pnvyxmfj.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gt2ivivjdgl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gt2bzohvgeh.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2hbvnxvqc.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2ggvcciwb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uopbmjns.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2jrqleqig.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2ocvpqrfk.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbkjohbh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gt2vwcwkbki.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrjsynjw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gt2fkpktcwx.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2vzxdksbl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gt2gzfpriov.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gt2luynxgko.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgufenzy.top/Article/details/gt2zxenngdt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gt2lvqpnyon.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gt2tjkbnhlh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gt2gkbpaqtv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2icqdrdbh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gt2zdsoqsee.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gt2ipbgsbsm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gt2gsfpjmlh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2cjuhkurq.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gt2xultdoqp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gt2bwmilxpl.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gt2ixphpvej.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gt2eoyscjnc.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gt2syyvnxlv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2jlrlgpmv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giciujlj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2rbpvboit.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gt2yhoputpa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2oeyaxzcd.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gt2syayljxh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gt2nwifupzp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afhsfcoj.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gt2luoqhhzd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2xcvemaiv.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gt2wniapnrj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2vaucstml.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gt2vmaywepr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2wksapohh.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gt2tzkzjbti.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2hmyxebsi.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gt2hthnaykg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2vrkhkbqi.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gt2liflytpl.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gt2keqsmnoq.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2dmdayfhg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2mqqwzctx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gt2uybpzrzr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2tymbdrbk.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gt2rkxprbtl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2czgpcxef.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gt2hscbtlmu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2sfnlqyjq.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gt2nvckdikk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2guogocim.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gt2xxhicgie.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gt2ercklkoo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2uddredpc.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gt2qxnlhidk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaguknsp.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gt2xbtkfqxb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrdagonc.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gt2kuyqnuzp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzgfpxld.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2omgqvenh.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaquqpho.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2mjwtsqxn.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gt2fdslljko.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gt2qgplwyia.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vogadajr.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmsqjagk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gt2srvmfzkm.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gt2txrnadiu.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gt2ijzuesgq.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsvonfld.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gt2mlczcwyb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gt2xswypiut.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzggeceu.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gt2oeefmttn.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gt2ptockyal.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gt2gfmqsnek.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gt2silwfouj.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2ihmctryy.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gt2tpynldkr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2iqqqvuox.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gt2yxeardik.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gt2jnzavldv.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2efvgnqat.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2avllxhal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gt2ynfnavrg.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gt2unakaldu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2adclyaoh.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2wjyxsyqd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gt2wowcppcr.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gt2qaadycqw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2vfbmpagw.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2tdcqndwk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anqpsiwt.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gt2wayrzngc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2wbjfazkt.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2vrgkdyvk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2tqxxeeeb.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gt2qywpettf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2euveynhq.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2hvwqtxtw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2jvnozczd.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gt2oamevhws.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2uarzxlkw.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gt2mjabvqpw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxzxsbs.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gt2ltxooxzl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gt2jubozyco.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2hwdueuzg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gt2qzvpswgz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gt2uucalcao.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gt2texnngcn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ewbovbzu.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2hygqjctn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2qysucsbg.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2cgdmswke.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gt2jejxglqj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2odhxhbbj.html


<!-- 参考信息 -->