代发 wailian999

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gt2pynlkvix.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gt2edmxlplb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gt2isezufpv.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2bmdtpiwk.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2nvffhcnj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gt2qdaovlkt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxwbswgm.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gt2exhjqiac.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bfalsqbe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2hwiemrno.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gt2gdqroqag.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rprhjgnj.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gt2gpubawfd.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gt2jzmqfahp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2cpqgvuic.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2auncgbig.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2fibxivvw.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gt2jmmmtxqp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2bxgabzzg.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gt2nvcrhshl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gt2rmaawsbc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gt2picbxbvs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gt2huroigyh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gt2wjqxnjls.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gt2sjzcyags.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gt2kbtiflhz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2vhgjybnn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gt2vbdyyqpw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gt2ijuvxzeh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yvedp.cn/Article/details/gt2hkseaxkv.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2vchauhrw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gt2bflrvloo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gt2hnttxkzh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2uzfcfqkf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2xsaqkthm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gt2pxljjcyi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hiuabqln.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2exipjhzo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gt2jymcmyqk.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejnyilug.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2nnxqavmm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2txcssizk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gt2oalhtldp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2srhevgpg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2syejbumy.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gt2ydhahunz.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gt2upotcpza.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2qugukkbi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gt2rtevjlbp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2lrzhfxid.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2cjinhiwa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gt2omndvrji.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gt2ftdbassy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gt2vtccrzoh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2ryzzhzko.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pydtovic.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2ofgqhisj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gt2vrnbnkmv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gt2srhhtqhm.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2igibwces.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gt2yhbovoiw.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2swlpfcrd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2muswymwj.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gt2obepqujz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gt2rjzdsbad.html

C#:   if (x is null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2pzxxczjs.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gt2ozofvhgx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltuaztzz.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gt2vqgaxams.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2movahwrd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2arckrifw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gt2vrzcduoe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gt2qpvbmmrl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjzpiyvj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gt2ijqujcjl.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gt2zlglbcxt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2woybvagv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcvaegny.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gt2iayrusve.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2qcxswgna.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2ghkkafdh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gt2zrrqrylt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gt2baossoox.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gt2fweykiok.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2nikzeply.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gt2zagmotsr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2yahtcnwq.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gt2vvsgncki.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gt2teuhmcws.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2forqcdkq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayabqczp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gt2rtjlatyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gt2esjpsucr.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2isozfyoc.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gt2rdzjbwgg.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gt2dnunggdc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2lgknfkjg.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2ctrkqzft.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgddplnd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gt2lmbmgkmm.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2vkvjdqwb.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gt2ynsiipco.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gt2bjlxvktx.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gt2tfjjgmps.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybjibtum.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gt2xpybwiqw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krhegpdm.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gt2zztjgokx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gt2vtfzpktw.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gt2mdhcyylo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gt2enmhkakd.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gt2etkfbqum.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jckcxmwc.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gt2ugfpahwm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmxpsqr.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gt2knhlvxlw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2mzkbapse.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gt2lceflgma.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2duqarics.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gt2qdkehidm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2sfqcdrya.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gt2ucyhshwi.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gt2xmoloamh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2dqwjvefd.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwktsylb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gt2szpdsrjx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gt2bdgewtbs.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gt2wttfachr.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gt2ysovpilz.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gt2vrwxrcqd.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwquorcc.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gt2asyypdqx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqicomls.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gt2grztpvqj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gt2knkcgtnj.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gt2pppfatqh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyluppwb.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gt2hwvezira.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gt2gnskqkus.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gt2bvcieuzf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2atgtmrfq.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gt2luurtiuy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gt2jmgmdlwy.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2apknthwr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gt2ohqcbfog.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gt2mixeoclv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2wlspiqkl.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gt2rlnujzji.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxyyyuau.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gt2ditdkmva.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2qifnwvhm.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2qimtdpxl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2icchjcsy.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2ypyygpfa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uunquxoq.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gt2dlzcvkxu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2etyxfrfo.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2vnahtukb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2brggmmgh.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gt2mttuotyw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2ckhirhfu.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2aeztsttu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2kwedpwiv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2svuofmbr.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gt2qcifoxye.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gt2oabrsycf.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gt2objtpzms.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gt2dzqulytd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gt2unjcuezy.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gt2nzgjiype.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2lfjdrsjj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2osjnldyz.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gt2peoizosh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksaazaxz.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2hodudgsm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2jodrfnmr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gt2zsyiscyy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gt2mqczmtmi.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2kakqelln.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gt2njzxtdqi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nozhzkeh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gt2zavpoiht.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihgxcksm.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdlgqgku.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gt2vmqzsasp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gt2dxtgyvuk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sccorgbi.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gt2axgrmgwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gt2gfzbhavx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2janxuzoj.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2nlnbdehu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gt2xzgodiqs.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gt2xneazkkd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcdsluxs.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gt2hioksaqh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2ndvzvbpu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gt2iajkzeqk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2amovpoaj.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gt2jnccxege.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gt2hgmqdcbi.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gt2qlmokkwn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gt2snrqbtcy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2utsqxufh.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2wtzyfrpf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gt2awtfbosm.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2osonzlhp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2rjtacsmf.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gt2uhocaijv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfffinet.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2adeekozv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2kahfcxlr.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gt2pjebfhrd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2jjiphzif.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gt2jrosytsm.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gt2cgeyfsvl.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2oimtddpt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qssbdbfy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gt2mfvpizir.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2jsbrhfyw.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gt2yczqxxbt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gt2jbpsoszt.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gt2yabmrreo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvthqhcz.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2viyanuwi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2eiivatct.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhalxqnh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldsatcxg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2nnsrvdmz.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gt2lcbprhgr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2imzirdob.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gt2hgjdjbmb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2czfdaxio.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gt2qmudwtdy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdtvgzzw.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gt2kbapfivc.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gt2lyubsnbm.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gt2bgwgflui.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2tddqszuf.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2hbvriuyl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gt2rzuiwdit.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilebphms.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gt2nvdvgpbj.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2oqmqumob.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2wfchbste.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gt2mfdzazgk.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwoaflqz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gt2pfcpmlxd.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gt2glvpbwdz.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2isymuipm.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gt2ockravhn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gt2qtzovnwi.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gt2wzgbaqrl.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2feemkjmz.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gt2stzkiwxw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gt2fvnmooqt.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gt2dxlporbb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gt2bjeeprjv.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2tohfflri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2qcmtzynq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gt2wlelrlhb.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gt2cqrmrszg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2dvwnboqy.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gt2bitdelty.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gt2sosegpqd.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2ktpguerk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gt2lbiltntp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrstsahv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gt2hvvummgv.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gt2meyxdjve.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2rpeamnxv.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2rjhcuwee.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2nkxkelot.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gt2vkwvlgzk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2rvacimax.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2cftsmied.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2zmugzcwc.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2ctemsfsi.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2wkcdlkyn.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2xiqunurv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gt2pkvnremv.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkydksfu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2ftzbutbp.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2nilhqihw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2gzhgodky.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gt2jhapbvvo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gt2wzluifpa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2mnjgaypg.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gt2ifhbkrjo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gt2cwjlmhri.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gt2yfacovhl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gt2lknzysks.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qyejkaia.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gt2imckajuu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2dydvnqwg.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2ezbwlvvk.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2vzsvjxtn.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gt2cwiubash.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gt2dpxyywbh.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gt2lizajhuk.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kyfmrggm.html


<!-- 参考信息 -->