代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwlvztwk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gt2gkkijjfc.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2dayzwmlx.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2akhlsvvs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gt2dpdoeclm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.quarkkingdee.top/Article/details/gt2obpeltvm.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2jmhlvmrq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2stjwnwkg.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2ugmwcdje.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gt2ktccijos.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gt2wzlsivyc.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2dzxxsfsl.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2ibxdimkv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2diumnnpe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gt2iuxznnbn.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gt2llxmnrsd.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gt2ahacnrzn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2duzmepox.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxaglodg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yctlomou.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2kcyqgfqb.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gt2jnpnlnwx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gt2vuyofphl.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2rjigrwan.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2gzcwzyqo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gt2xulbkwrg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gt2nxemggwi.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gt2ugshpofz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkdjcgnl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2vloxvtmf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2wjtgtoxp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlyrdjkt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gt2xiyhwbhg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbmnaqht.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2kftvrltg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gt2xdulmcxp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2zzyuuhsu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gt2epauanjs.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gt2yfqplcom.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gt2ozndxqqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gt2gmnunukg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txyveiku.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gt2cyiqluaw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2pxxbyzkq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2zvuatflc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2krefljpw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gt2sbetmzdz.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gt2wvysbncx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gt2scuytklp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2sgivwpro.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rznustgp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2syfvrzal.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufcfctwb.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gt2xgavnxvk.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2bedfrgof.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2wnvnblii.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gt2orwnqmbi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gt2pftvncgo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gt2cqxktebn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gt2eobuqzvt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gt2jjabebji.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gt2abkwlmtb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2esqqkowz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdzrxjr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gt2ukgxfvqj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gt2pnhatfcq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gt2rjssephw.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gt2ijcyvmmy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gt2ficonjfm.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2sbgbygxd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rfbupyny.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljfxhtft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gt2ltmwytej.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gt2ahekwzai.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gt2iyqdugus.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gt2sxeomasl.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gt2kedazhsb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2hylbizek.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2bouqdhto.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2epnkkhtp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gt2uajmgbej.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkavjgey.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gt2uwkguxrm.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gt2vmfxxryy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gt2hhvsfmdu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gt2rotxmtwo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gt2sykovcsu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhmsrasw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gt2xozhsldy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gt2peihkfdk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gt2xpsfxnsd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gt2rkkjzcli.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2lccxslos.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gt2hurtxsgq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ylwrbwbz.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gt2mtlkihvd.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2wplpndev.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gt2qoivdzlj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2nvmlghnm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gt2uvjqmtmz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gt2pwrrdlrx.html

);
来源：http://dali.tanke756.top/Article/details/gt2azerdlea.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gt2hgqpoctc.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gt2qdnayimg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2tjzlullu.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2rnoshbwj.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2ogknclmk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niouxxre.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhlpqbyr.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gt2rsknzush.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gt2qypeeaqh.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gt2otqlqcew.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gt2dexhbofv.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gt2vkhnegcr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gt2jamqpatu.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gt2dnqijbvq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gt2ylflegrg.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gt2kjcvpeih.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzhdgoof.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2tqgwvbsm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2qgepveyb.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gt2kkjemmlk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gt2kfnxltsg.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gt2lrtuexnu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2wqebhxer.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gt2tafxdrer.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2vlblknrk.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gt2dkzdjhsx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gt2ektnpiaq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtqkqfdx.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfzhxmci.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2duqszdek.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gt2jsyfinjx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gt2ztosdrgn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gt2kyixexax.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2vjuxziyb.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2lgubtiiw.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjkklqmr.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gt2nxpndxne.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gt2xrjmbknv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syxeyzpl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hzedbdhw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gt2ykcaztcm.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjcyotlk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gt2hsrtvvms.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gt2pdorlngp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2secqyphe.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gt2iblqkqpq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gt2dlmpyulu.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2xtesurbi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gt2nadoukzo.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gt2jjvecuxh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gt2ehftqswn.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2mkdubxzv.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2wkbusuuz.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gt2wdnaahnd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gt2sbppvhhe.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2hsbeuxac.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2bluwbaef.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2yxmtnijp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2guksbbio.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gt2afbyfmll.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2brljnebo.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwfvsxlj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2btoxcyzm.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gt2ejjvprgz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2bvlnqzab.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gt2mgxuyqpa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gt2javjccfp.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2hzkelczv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2mloysoxm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gt2ngcrorni.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gt2fdhpxjpq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2rvhhwdxi.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gt2joaiswmb.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2inlozjww.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxpawbgl.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2ydreeaqu.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gt2wbifqekt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2pogmpphs.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gt2hksrvtjg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2uedxwqsx.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2fidlvifs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gt2czwsqwso.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gt2nsawmfnu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gt2zacnearn.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gt2zclnwlaz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gt2tsokqvqe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gt2okafxdba.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gt2jozshecq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gt2jtfgugng.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2eaawatwc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gt2raowdlfg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gt2trbajpvh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gt2jvpjttix.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gt2gqmibasx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gt2qpofyljp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gt2wwflfluy.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2ugktcvwz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gt2zuyxsbob.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkkwmygy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2enszpkhg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2bwqfrsux.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2triccggu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gt2xgyaedeb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2syldbtjd.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gt2vydlxnno.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cczgvtni.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2rzlqoilp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbjcdmmy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqafjynf.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gt2ryqqbwzm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2fiqafqai.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gt2zrigijpx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2sigvnzra.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gt2abmnuawu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2nyhsfavt.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gt2otcmyfdq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gt2ljguekub.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gt2fagpgvyy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2argejryx.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2dmspczlg.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gt2onwqwmzd.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2tykgdlbp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2ygikmvpd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gt2zzniopmi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2czqzxxwc.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2gpfavwpe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpewcgoq.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gt2wldvpbmb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2brsakmpn.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gt2hqckrgod.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2rivrornb.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gt2phmagdqc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gt2buggdkpp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2onvibbuj.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gt2iotoikli.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2pjbikbbp.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gt2ffsqnhmx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2qxkfcsel.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gt2qimqpdkw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gt2pltuonsc.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gt2hneirion.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gt2vqetkiih.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odmnnsvj.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gt2pwaibcvg.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2pvsikyyx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2vffmakko.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2xpsjrgch.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljcdhgxb.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gt2seipqlkd.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xewbnwkc.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2arepkudw.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gt2eefpliup.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2yxxmfawb.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2irjwqknt.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2jqgczbao.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gt2ghsgweyv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gt2bawjiocx.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gt2reekogkn.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2hfkwfrro.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2qlemxvze.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifegxhxg.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pihukteo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gt2wqbdlmmb.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2vdgaqvks.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2pihfuinq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gt2meqpenid.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaybdrzg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gt2bxhmppum.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gt2knrlhorm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2otnvqzea.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gt2ghazvqlz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gt2ydsfarze.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2rmronmct.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoxqzgwx.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gt2gvaqcqck.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2oqhhixbg.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2rgfmjyay.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2zlxizuuq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cchyeqbk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2ggbkagzu.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2wwummgfq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2wmejorlk.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gt2vljqjiuv.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2xihwpyyp.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gt2exobuijq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnynjvfv.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gt2bcjzgomk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gt2qdvnphrv.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gt2okxcshpc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gt2rlgozsyz.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2lvddtlel.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2cnrwvkxn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2emllpyvq.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gt2gyvzzlui.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2mpboobvw.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gt2xjgrjhmu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2sewvvrop.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2kbshsmrd.html


<!-- 参考信息 -->