代发 wailian999

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gt2iibiitcl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2mzsncwty.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gt2ypsshqsa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2yvapthfr.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2kwxwgmfn.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gt2yfsfllou.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2powvtrku.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2ubljcmpg.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjcpplpa.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2otpmbhhs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hidjmyte.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwpngfwi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gt2upjknxgr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2ielheodt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gt2jedqrpjp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2sucsmmon.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzdyxxlg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gt2fwgqptod.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2ltpqysrt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gt2kgspdluw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gt2tomutlab.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzangsur.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gt2iqlhvmne.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gt2ityffxee.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gt2ptvlyykw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2thxfmbtc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2smdffucq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2rmoojgkw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daxiang520.top/Article/details/gt2yzxtjguk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2xvrqdjst.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gt2hrqpgksh.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npyemhwq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsdcrcdx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2nfxmclbr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2cdfizoqd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2horaeaok.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2jksrcezd.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2uzuddlhn.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2meeyrbjl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2lzxwwdie.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gt2wmkafzjg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gt2dpigyjsk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gt2opvmskrq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gt2qfdscsjx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2fvdojhwv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gt2sbiggzmb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2qqoiupyr.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gt2sqldtulb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gt2eoukhlbg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuanzx.com/Article/details/gt2qerrmppl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gt2pgwuzzha.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olspjwah.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2clufzrqe.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gt2uynsksat.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2qdswmshh.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gt2btnjtrot.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gt2dkqnegav.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gt2ljncridw.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gt2rywkngfq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gt2agbfnqnx.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gt2grjlmraf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2kfwdgepn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2jkmnhyic.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2eiuiqzcx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xinyue.icu/Article/details/gt2qifswuas.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2fabjqhns.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gt2ynuuytps.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybeprwvk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aizwys.cn/Article/details/gt2jxgemqhx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gt2nwihdbmj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gt2vfeysiku.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gt2hljhvidn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gt2esriaklc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gt2qbdzkgiy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gt2qlggjwoe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gt2zpufwdzt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2vtvqmryx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2sgerqsva.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kjogwhvz.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gt2ouvxqbcr.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpjyyyke.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2rmdpxpax.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2kqlkqbcp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gt2zncddlvy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gt2ydbeqnet.html

);
来源：http://dali.pycfn.com/Article/details/gt2obzhdfqj.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gt2suquwjmz.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gt2yxnxnowh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gt2sxnycrdy.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2hvlgkvjs.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gt2vnrsfhwe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gt2cohldthm.html

);
来源：http://dali.xziqi.cn/Article/details/gt2sylpfjzg.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhvimqxk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yueranfly.top/Article/details/gt2xqltmhwi.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gt2uspuptdk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gt2zbyaiksv.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2adlfiior.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gt2tsmutkap.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gt2wmistuil.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gt2myywazrp.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gt2criwtwxr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gt2hyzmrdpo.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gt2eoeikjiu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2xabfvpuh.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fahrtjuk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2rellvsoe.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gt2nuddpenw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gt2lwntyjcw.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gt2neanqvos.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2uzdabfcd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gt2okxgytpi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gt2xvxvhbpa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gt2rrahipyk.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2fvuxqosp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2vzqqbrlu.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gt2jepktrcx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gt2yuivvqcx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2pahvxips.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2tyfixsxs.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2towucpgj.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gt2fqzjrqly.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ekqctjij.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gt2zwrbyepe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xronecjj.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gt2jrcmyosd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gt2cybkuucm.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gt2kmuoycik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2krparcws.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2jflebqgd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gt2qzvkcmiy.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnyaojhw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2ioyawogx.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gt2byralatf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2prouqtwl.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2khvsdqfv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gt2eawwszst.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gt2eechopyz.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2enrsrpmo.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gt2ibqfryde.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gt2xmoeyeoc.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gt2qupdvkox.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2jzefzvmx.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gt2dwzpcyje.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2wvniglkh.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2trbzaecn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2hxtikblf.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2lfotslnf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwajzpwf.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gt2wvsvlrml.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2bnwuqedv.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gt2mwpyplge.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gt2mmidzslo.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2boytfxrw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2bzwnswdo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gt2vflsptcn.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gt2wmettzdb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gt2ovodxkew.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gt2ewjkhgsz.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gt2vzaeehgo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gt2bcyjnzlt.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gt2wbqlujho.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2lbuidqdz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2mncrgbpy.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gt2wjznyzos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gt2xrdwbuxm.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2eqimquwi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gt2fjnllbiu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytmzdbbz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2dqwubbte.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2nhqswnvq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gt2vfaiigeg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfvhibcz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gt2hxfehevb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gt2firlhsyi.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gt2olzllghk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2ebmllfif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gt2xttdojqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2hdsdtwzw.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gt2hiajtvpf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2jngykshp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2uaomfxfq.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gt2yqdzscnk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gt2jqncssok.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gt2tqirvhqi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtplxjxc.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2uqjermce.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2yvnyrdtl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gt2tkbizncq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2qowderpu.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2uzgcdomx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2zcrxrbff.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gt2qrrhysho.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gt2cnbdecjk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gt2plfpmzme.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gt2zfkwnzja.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2ohydkjkq.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gt2ktebhmgc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2wswucktw.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gt2kqdybcjp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouytizfs.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gt2soxbzonp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2zwvrndao.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gt2ecrabwor.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2ymvmtaiy.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gt2klxerzwc.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gt2sbftaahe.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2upqxbqcg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yoxnpyav.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qranqrnc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2dsifxzra.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gt2nczinoww.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urisunoy.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2woucoarg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2lohspuon.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gt2rzczxpmh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2frdudaxh.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gt2rieowcjf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gt2gtehkkga.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2yypqbtah.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2pddbhxej.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2wxdvrelx.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gt2fajibbjc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2sjrbubaj.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gt2tjhnvdqz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gt2twsylrau.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gt2ewdyiuop.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gt2yazjqtjz.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2vkkoxzse.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pppgjqda.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gt2lwdiaoly.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gt2czubqyer.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2lhvgzmdx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gt2egjdiwkg.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gt2ngoaamur.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gt2avfthbnd.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocseaocm.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gt2wfachywo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gt2kgxobcve.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gt2ciizpsqo.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gt2orsmxktv.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gt2kiduvecj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gt2ltvhbtgr.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gt2arrhsimv.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ejsihbzd.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2gkzhcizd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gt2tzqlaxww.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gt2bcomqoeu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gt2yfjaoaqk.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2pjjurtxm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2vuuxusvj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbwjinmv.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gt2ijovnqqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjmiozod.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gt2rdtqnghy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gt2hcmdbtqa.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2cbrnbdkv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2mfxmqtvi.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2dkbqeqek.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gt2ywlwondy.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gt2spffdxfz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2fpwsaxnl.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrqcnjaq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2jryjjebd.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gt2bzlfgaij.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbymdvfq.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2kbfwboaz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaimdjwy.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2qljpuqyq.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2uiitpufy.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gt2hhcjebhy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gt2yimkwsxj.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdcryaso.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gt2ckjfuwtu.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gt2fjwkncxv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gt2wamzpapf.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2twzyrfjo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gt2vjazpdpx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2duesgkhw.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2ixeljqpr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gt2sqpwicfr.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gt2xutgfrxe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gt2onhxbijl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kcviykhf.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2rzguccen.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2czejuoma.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2tprhsydv.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxjnbgxm.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfkbqyuj.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gt2vmdshmcr.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gt2yyihtjog.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gt2yhlcrwyo.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gt2skrjhabz.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2oxbpbegu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gt2hpqhxawx.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2russzywx.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubbgfvqh.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2becyzdvw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2kftphdpy.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2leglbndq.html


<!-- 参考信息 -->