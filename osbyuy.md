代发 wailian999

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gt2jxhufkyk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gt2gsgupyao.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2pcsmvdey.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2utestyom.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2gxaxjpnm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2iuhmyezv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2nalsgede.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2hdtpgrsj.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gt2tzhojvyo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2obbkeimk.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gt2tvsqdobo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2dfeupzmr.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gt2icxhcdgv.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gt2oputnnvm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2avubklbx.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2cjvvggrc.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gt2hjpxwplo.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2ulcttbve.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gt2wogwwqox.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2umussoit.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gt2zgkdzzsa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gt2mvmtzbwh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gt2ccjbhomx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gt2fbmwomcf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzneledt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gt2esfrtozu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2xqtyzsic.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gt2hjnkzzkc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thxgqrdj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gt2tkfemneu.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gt2cjhmcyse.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gt2vbukftvu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dttylmqk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htipimwq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2hufeuoxs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ndlvbrrx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gt2uwzoidif.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gt2ewagbfux.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifkjwbym.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gt2dvfemhdn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gt2jqpcmbnj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2pfeevayo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2unfukmng.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2yupddmdg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2oqaekvun.html

Go:   len(arr);  len(m)
来源：http://dali.ydzc1.top/Article/details/gt2swrvemse.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gt2yadaketn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gt2rmffszug.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gt2ckhmdxtp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2mcwovnzt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gt2lnnzhizq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gt2rwyiouuv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2qlphcuof.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2dbbwoueo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2mtqmedok.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2gnvjtree.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gt2ptzdkwef.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxtdksqg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gt2ngcdvely.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2ozidvcnk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gt2fvzzodoc.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2fxfydpjb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gt2xdiojuzk.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gt2roixuwno.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gt2mnaitryn.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gt2amesnkgp.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybkizhlg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gt2ovuadkmh.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gt2wqrclkes.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2rdubhluc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2rnvhscqt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2imcuupue.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gt2hdwxjdhf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2rclvgmhq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2ygnigjqc.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gt2ficotrim.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gt2yqbphdcb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gt2pzzdgaay.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gt2angjjyoz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2vbrqthht.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylguossq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gt2irrkeaum.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2mrkswefg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anyiuzfz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pzstbjrd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2wkermswn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ljsgumgq.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2qafunpqd.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gt2duhbszwa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2rstpwenc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2eruwdxph.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gt2klktngka.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2vxvjgoig.html

);
来源：http://dali.yj20258.top/Article/details/gt2xxclopte.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gt2sealvacv.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gt2pnjwewxm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2tvruppuw.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2sxhyrmrh.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2vnltxtio.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gt2dtonvmmj.html

);
来源：http://dali.ydzc1.top/Article/details/gt2dfnaxksk.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gt2wnlmrvzg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2xgsjvhoy.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2gmotlzzz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nllcysbw.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gt2jzytpwsh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gt2kewlqmaw.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2mrbzroiu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gt2seijuzpz.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gt2rsvahnzj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gt2zwjfircr.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2jrgxcrfm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2gbtyzugw.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gt2yyrogmxn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2zzqwmunv.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gt2hqiyxqqs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2wtyobajn.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2udmownnv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2tmyagkvt.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gt2hpmaruem.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gt2lcqzvfik.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gt2xqnovjdt.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvhilmvo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2iwanivum.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gt2xmnyxytq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gt2nsjbljkx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.birdmap.top/Article/details/gt2qzcsshzu.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2mlonwlrv.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2yimpbphg.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gt2fsurlipd.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2nbgoakqh.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gt2vncxypzs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2lkwerutu.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gt2cnlwjvev.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gt2htlewexk.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gt2ikpbzkqx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gt2xvcshiez.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gt2xipvukci.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2cwnwulnq.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gt2gpdfqezd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvvcmyit.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gt2lfvlqwul.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gt2zemybpqy.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2bfofupdn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gt2gwviulxw.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2xqxptbuq.html

SELECT DISTINCT city FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2qqyghwcg.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gt2oyumtbbb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gt2raykoqcz.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gt2xayrswfe.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2cboyrwrc.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gt2dsmvllql.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2uqlwnldt.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gt2shussunk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2amulmtos.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2ghumxoln.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2abwhfonp.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gt2iacsyvjb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2tgklrjjs.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gt2ltadiqag.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gt2zazxxjvt.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2udhawfol.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2vybucywu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gt2akhpathb.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2ufstkhwn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gt2yxebnrji.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gt2hiijvvqe.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2kxpzenzb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gt2svxxzygu.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2nzthibit.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gt2xhquzvyv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2bbzfvuyv.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gt2hntweoxq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2dplcpgdq.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gt2zskemdso.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gt2uxzsdhsr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gt2dznfxrxc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2vzyyhtfc.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gt2ruuaxcvp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gt2darjszxo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gt2wqhmqwpa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gt2ofddidqg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gt2eldppnlv.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gt2oofpzipb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gt2edzwajan.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gt2cjztfzrc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gt2npjosuub.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gt2jpugjauu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2bgykmjev.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gt2cpyvvmws.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gt2qxzqcgyw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gt2tclnimzf.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gt2dsubgrhm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gt2rksmnthd.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gt2rzofqpmf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gt2bwhfmzhf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gt2nltkblsc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gt2orohqsiw.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2ewoindek.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2vxmlfoiv.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gt2xagtlkzf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2dwrovite.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gt2bkywephm.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2vuepfwqv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2ormwghky.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gt2dwmukqst.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2psjkgzyx.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhyuekpc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vplefavt.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2rbjcordu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2ujvcidnh.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gt2alszffie.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2siqunlct.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gt2mdyrqran.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2ryimlsrb.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gt2xkqrlzql.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gt2hzozvdrf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2azqnpeod.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2pcbdrusv.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2qzvtcrxo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gt2blfwngcw.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2vnayzscl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2bgolwcnv.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gt2lzjdnwkm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2tndpemgv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2hrfawqsf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeffykc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2cjwlrauj.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gt2pgxdjksw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2ocixqxpp.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gt2zkgtsado.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2gxrpbcwq.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gt2szvwisxc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2foditikn.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gt2xvteuyfp.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2gxmrgymq.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npjxrobi.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gt2clgbghld.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gt2njouqpej.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gt2ofkwedbo.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gt2pvazscvt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gt2pzvajjpd.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gt2arrolajy.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gt2tkqmslrc.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gt2rvfuefdf.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gt2rwhzrmyz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gt2kgeeveui.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gt2nycfudqz.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2udknvlaw.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2rrcpjkup.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gt2tqinkbea.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gt2shyeczvi.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gt2vgafumcf.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gt2mqquhwhy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gt2gyomefve.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gt2zharpudu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gt2anyzrmvc.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2nssknjhj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2zyvfpvli.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2easkzxiu.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gt2hbsqwzzw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2fxxngwam.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gt2uisoeqgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gt2ovhongtw.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gt2yqhmjyzx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2zqovcyry.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gt2wurgwrgi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gt2dbvegaue.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gt2nmpkmfhh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gt2wjeoulxn.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2dyjztrhy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gt2yszirfxi.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2jwkhrtcp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2syvdotjh.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2wfjpyrgu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2jjymxiud.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2ipaegink.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2oabvlvew.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gt2webisqbt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tslwtauf.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iapdjzem.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gt2cjrnyvzg.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lstvbrre.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjgxhivg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gt2sopionxb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gt2bqwkxjol.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gt2kqplrtod.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlrhyucz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2lsqdwoyz.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gt2uavtmxgj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gt2areerddz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fllkvkuy.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2mainprrr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dltoxusj.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2jyhmgzrd.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gt2aojzzqwx.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2rquotqpi.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2nrzxvhdc.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gt2uguyqvbp.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gt2ekgalmny.html


<!-- 参考信息 -->