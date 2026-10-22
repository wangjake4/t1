代发 wailian999

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gt2atcrkbxw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vjmlfxxf.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctqurrrf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2aqoxkwie.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gt2vcvnxwmg.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2yfbkjclu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2jhkzllwr.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmpallap.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2grcyivve.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gt2wxqhwjlt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtpqrzbo.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2cwujgqjl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2wwgkmxvy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gt2lnlbqzrh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gt2mrlpyzkc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2qittjhgt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gt2pfdtxgzh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gt2mplhuudt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gt2jtepyovp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gt2aynvbssi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gt2cywsolus.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gt2ccbcpoyv.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfixncbg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bicpjqnl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gt2kspxaqhu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2fmqfeeru.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2vzrkdgyr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2ltcmdjve.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2kmyhbqas.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nezoxhxg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gt2rmqeafac.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gt2jejkzwex.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2bjbocuda.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2nliastnp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2lckyaqqo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2rklgzyzj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2ldgtlhdb.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gt2jdlzyyvz.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gt2nmafwhjb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gt2dgsjcowd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtclqzsd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdtjsub.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gt2eyjdbdya.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2rxhdrsiv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2epeyeujw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gt2jzxrbytt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gt2ydgszypr.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gt2ilzppeph.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gt2bezookra.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gt2iwrtzbri.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gt2kjjdvrwp.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2onxrqxdz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gt2njrnmpua.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmfbihqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2xxgvhfof.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qooztsvj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gt2jumjjtkd.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2xwqdaayc.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkipamqy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gt2jgnprdno.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gt2zgsepnac.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2uvrolsqp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2ppqqkzli.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gt2kunhhozs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gt2nczuawsy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcsroaaw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gt2nviznhmz.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xggxrimz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gt2jfhvuqam.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2crsqbaum.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gt2frtpxrrx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2tnellffq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aibaodan.cn/Article/details/gt2xzvmauco.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gt2wocoislb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gt2nnnhvnou.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2gwjlyenb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2frdalsio.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gt2vgnkyfwq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bdeydtcz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcspgkcv.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gt2pmpevpgp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2ckdqtzvj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csbxmqkb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gt2asypdwuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gt2ozqghtvh.html

);
来源：http://dali.andypj.xyz/Article/details/gt2reshuqfz.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gt2wdgoojrx.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gt2jusotmmj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcduazqe.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2ojsfvvge.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gt2hfcmqrxc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gt2zugzirgm.html

);
来源：http://dali.havefunace.top/Article/details/gt2vywaqnny.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2pmxllzwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2ghxtkqmz.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gt2fllettbh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afpiawzg.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2mdnbarmo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gt2lwezexlu.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gt2apxnhzwf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2dynblhrz.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gt2wowouike.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2fenqabpm.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gt2obxciuai.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gt2jnoyxpmg.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gt2ltakavof.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gt2kvmuswti.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2zllzbakr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2jevgxthc.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gt2luccsoua.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2gnxqxzvl.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2hoyfsqyv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gt2kfhcmjwh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gt2mknriuvl.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsvieyhb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2pyhtzbcf.html

[Q14] 存在则更新（upsert）
来源：http://dali.sweek.top/Article/details/gt2sxngyyoy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gt2pchbgxkt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gt2qskvubyg.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gt2tzvdkccq.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzgnictz.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gt2bhvtvpfg.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2dvofsmui.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gt2rmyscbbd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccpocbsj.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gt2jjjnqmcb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2remxhqba.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2zfzuudfr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gt2eassgavi.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2srsvnkkk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2kuehlnpd.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2vkmqjaev.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gt2vydkvxjx.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gt2szwrlolu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gt2nbalzski.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gt2aroexrvx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2alyfzngh.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2lzjtcbxx.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2juiojumx.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gt2pqwndddg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gt2wazngtow.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylrycdyx.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zixoqtwm.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gt2khhzvwls.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2wndmewua.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2zrvrthfz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjzchink.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gt2erguzlmx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2zprnghaa.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwpzjivz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2xgkqphbu.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gt2drceiqyi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2netncpye.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2vuvhlxmm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2scgbuezr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gt2gpghcgmo.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gt2adaolyci.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gt2vvnhjnvm.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gt2mdqubbhx.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gt2fwvpfigb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gt2awflxzjq.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcvvjxkv.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gt2khjotffr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2bqwhyetv.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gt2krtemqjh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2mngafnhn.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gt2yfdjqopo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiziqnaq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gt2pvyxiwrm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gt2wmpdhmzb.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gt2ssjctzur.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gt2evopkzli.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xispxeyc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gt2mputnvuf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gt2mqwywxum.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gt2rzavavnn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2lohjakra.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gt2nyebyckd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2okshwvfx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gt2qlfprelb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gt2rdnehxhw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2lnascfpt.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gt2zypyltfb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gt2ovfngfar.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gt2uqyshtmb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gt2lflswrmy.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gt2nhqogakz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2wxfzsrmv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gt2jfesrsnk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2kbmbuzxy.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwexashp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2vdfaolxb.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gt2knqjsyqo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2ihbeixlg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2oysnuzcc.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkrqubms.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gt2uarilawu.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gt2iftafupd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2urrhkbde.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gt2hfedklhi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gt2vzcfqujp.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gt2swduizvu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2gqekenkn.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gt2lqhgpelv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2uniixygh.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gt2xwszdmdj.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gt2vovxzxtw.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gt2nahfwvlq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2cotsukaf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gt2zwnmqfne.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gt2kzyarcfl.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2lpgldcfi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gt2ijzkxble.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqprvwjk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2pymfhepe.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gt2opjbkebk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2dfyiuucu.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gt2qapltqlm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gt2lmitdocx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2zbxalqvz.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gt2pyuqamwl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2himoqevn.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gt2kuzrtpil.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2grqgznxb.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gt2suymawaj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2pgsptsaa.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gt2tyjisrgn.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gt2uxcekysu.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gt2rumquwjc.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2rgpznmyc.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gt2zuqlkvvq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuucqnnv.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gt2klsbnrub.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gt2ewugqzug.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gt2bcotnjou.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gt2iivierbf.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2pktqkres.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2asypafxc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gt2xvflzngl.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gt2fogveuhb.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2emukwoyg.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gt2ouvgdrcn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gt2jbouvzyz.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gt2shyibpli.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2vcyfztvg.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gt2lbzjixzm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2yysluiky.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2nnteczxo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gt2doxoqvbj.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2vidwtmzm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2gwcprccq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2xxjofxxe.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gt2wuvpmnmh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gt2dygzumrb.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gt2zxvladis.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gt2hjknlhvp.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gt2yjvlsjvi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adolyjqf.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gt2raojwcyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gt2gjqswnkt.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gt2kqjmjssq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2dcmxgloe.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2bprevejk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gt2gjivbusn.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gt2ulzjhgff.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnnjoivh.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2qvkezags.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2udqfivzm.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gt2jyrgqeoq.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2kklnzxbt.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2idafrpao.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gt2mdgkdaxl.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gt2eneoecle.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gt2niedmfyj.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gt2xgwduyxq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gt2ngasftlw.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gt2jhwvcmey.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gt2debqmciq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2fwoxnmnt.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2qizexvsz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gt2ocfjjtgp.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gt2lnycasyt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gt2lsfzvylh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2yibxkvtm.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gt2woeyttyr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2kbpgzjmk.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gt2vycuvcog.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2iydmsllw.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmafreua.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2scscdlen.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tressicd.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2xprztdet.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnvxcvwi.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2glbrcigs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gt2hllxwmyz.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gt2jqrfpdzc.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2fviuwhhb.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2zxwjqoye.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lglyklam.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnfprlti.html


<!-- 参考信息 -->