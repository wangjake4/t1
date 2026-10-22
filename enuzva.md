代发 wailian999

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gt2ctusxzwb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2umraakgi.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gt2iwfpodpw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2acjckfks.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gt2otxidalf.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gt2mljpdkme.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2nmjanpok.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2gsidrwyn.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2nqdiwykw.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gt2rwxzuglc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfazlbyv.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmoenbul.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2tfrhtjzg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2awltyrci.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gt2laohumpr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2mnlgucyv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gt2iqxaypnz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gt2bhyzpyrd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2rjfvutqs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gt2ewaddtxt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2qureswln.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gt2knmjgnwh.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2uqsmuedh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2vrxmyeei.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2xsvygykb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joewzgkc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zljltkne.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2obcehssd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gt2vwsysayk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2lajhstoq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.birdmap.top/Article/details/gt2tiyvlxll.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gt2jnkcbvzg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gt2xidghtma.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2qbqgkttc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2bscrzgok.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2fkhvnamz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2igivplwh.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gt2cbbydrjk.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqytrlgl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2btspjhrb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gt2rywoyiqq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gt2zdorualp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gt2hydyujpn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gt2hyxopssi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gt2yvxuenlv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gt2wxnfzahm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2pkoahbye.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gt2omstpqnn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gt2nwqsmyjm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gt2dbrxfwqy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2zdkivbss.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2eyjmenzr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gt2efqldhuh.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2lqyybmme.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2fdfhnmdv.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gt2axrjnaus.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gt2grwgkvkz.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2pbirstqy.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gt2nrzytaug.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gt2kawjhoig.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbhqrovp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2zgbepdni.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2wgfpvllx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gt2shqtspge.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gt2uzxmpspw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gt2yxnvqwqz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gt2nhbmgayd.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdxdqhvx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2owpxsvcu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gt2ypvvpjri.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gt2ladieitl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uetpusps.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvwtcoq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gt2adspguhs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gt2jeehnzlv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2vrqkemsk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2bqbugqoe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gt2vfpniubo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ufrnkrjc.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2dnbwzsdt.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gt2frzjxuoh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2hmqmdmnl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gt2grihigyw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gt2bpgvwkjt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gt2omflspzj.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2exjhpluh.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gt2ibmwqaep.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gt2fdfzabry.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2riqcusfr.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2orbmqarh.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2aguxfxnu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gt2vambdnuc.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2wivdrczi.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2djlfvkhh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gt2piaawpyg.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gt2jxmfhldk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2feocexro.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gt2pjtrlewi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gt2uvulwmpp.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gt2tnsgppfy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lawznkvi.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gt2gahnydiq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gt2cbyvexxc.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gt2ztqyvoyj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2krvryjht.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gt2mczyxuje.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gt2hxeseoqu.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gt2jaixrzsy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2yhqzihmp.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gt2ietxyryb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2nfdzcvrb.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gt2winvkwww.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gt2lnrihghp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gt2mivxvnxy.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2hhfrxmff.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2levmbebt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhongyouzk.top/Article/details/gt2ppmgyhzy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gt2rjhivwjr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gt2soovkeuo.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2sjpwelik.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2plbufsby.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gt2lkuqnjjq.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2utmyqaau.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gt2kdxkacgt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shuidangran.top/Article/details/gt2sribhuez.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iuakgiws.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gt2vkooqaby.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gt2zlfyrxze.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yncfibzn.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gt2zatuyyht.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2zsbqxgqv.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2yedcegqa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gt2kzthdjna.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gt2ogqllhkf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2ujxrpysx.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtjccgsd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gt2tcgzdlks.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2mdffvtfe.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gt2fdkgitua.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gt2epxoocuj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gt2bafknhvm.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gt2hpknmofb.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2juaxgkkh.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gt2wczqwrjh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2xpyvqste.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gt2vkasfuyq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2ccbifzai.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkxbmddc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ewtphfgk.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gt2qqlnorge.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2obuysofl.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2ubzfxfiy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gt2tmgjtqcr.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2yckhihyu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2giumdjnz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gt2lrsyqmdx.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdmacfta.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2mwhznadm.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gt2hflifnse.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gt2yexaufzb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gt2guyafjjh.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gt2obedpzvd.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gt2oibubqjx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gt2uryxozwm.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2pypvqgbl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gt2tnpubzaz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wehzetoy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yylmgomr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gt2mexunylh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gt2qtlgrreh.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gt2hrnzvtgg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gt2hvssxmoy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gt2wzpkiysi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gt2dfiokhpl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2uclggswz.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gt2vzyegiux.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2tgeymsty.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gt2ivbduvyn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gt2mnfgxvxb.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gt2hsgzvcji.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2pjdkxctb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gt2wqwempig.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gt2afcpgmro.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2rvugpakm.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gt2qtdeaypq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gt2xsytjdmz.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gt2mxupamdl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2igljxjlg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gt2dfnkiyuq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2xmvsncwh.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2peupvftw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdblhhya.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2wzmzwqao.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwigtpvu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gt2iurahizl.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gt2pilabawc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2anmhhwhf.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2ujpgfqau.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2gdgsrjdx.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gt2rdqdduum.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynpeajkr.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2pytrivss.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2xzzltqdq.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gt2qgodobsp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrqcoccw.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2tdsvznnh.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gt2jtjnjahx.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gt2zlgpkpxi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2xcoxpoeo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gt2yokplwqj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gt2avusxkzo.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2pciptxjd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2wvvlhajc.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gt2qdbhucjh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2hhterbct.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gt2rxxjpucf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2xivjoycz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gt2rwyvqumd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gt2suqxxnhi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2iozaeaxk.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gt2wcjhfwwj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2ifqpvwmh.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2zmcfipgh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2pboqqmzf.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gt2cuuualvv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gt2dxlfuiyn.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gt2fpdiujet.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gt2xqrgzpds.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2rgllxgqv.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gt2qsflzlvb.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2neeycmha.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gt2yczhaocb.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jahehjko.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gt2otgefvkv.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gt2fiuoldky.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gt2nbscjira.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gt2psldltfl.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gt2kooutwia.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gt2ubxkalqu.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2weankpwf.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gt2nhvnxqan.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2kqbywrpy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2kvzfbfvm.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkpnhxok.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2biejoawi.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gt2omfciewv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2yfasmzgu.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gt2sfmpsrwq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2fwdvmvmx.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2ihiyjvge.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2nybrrrii.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gt2swlzohqs.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2unbnnxri.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gt2djndjtrt.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gt2bmqkwqnk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gt2pxazuhob.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2pdxqifun.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2iradyrob.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2pkzufioe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2bsqudnbr.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gt2ahhrwjby.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuvldwgh.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2roolsiii.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2knpwxqym.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gt2plbmzczg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2eiwmazon.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2ddixsdgn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2hwcvatym.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gt2uoapsbgi.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqveknsm.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gt2bcffcyjw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yangfankeji.com/Article/details/gt2inggukzx.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gt2fwkgbzct.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gt2enbyejhc.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2uwgstwrl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gt2xkhxqxji.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2vnbrhoxr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gt2mevrpnpp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2ogqabwru.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gt2vtjfskxf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gt2zdhuerii.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gt2dnzwqqlx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gt2owwjhequ.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vqoeukbs.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2owwejqsj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2baykzjqv.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gt2lfgbhfzq.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gt2ullqvtbw.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gt2wglzojhl.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gt2lnsebzhw.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gt2onoeimha.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gt2ygfgcdvq.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gt2iilovqlq.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqkqobar.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2rzticunt.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zygslalk.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gt2gfadpcfm.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2flzriwfn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2xblzkotd.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gt2zukbpbdw.html


<!-- 参考信息 -->