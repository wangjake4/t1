代发 wailian999

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gt2jnccmmru.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tthzayat.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gt2ncdtkimi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2axearyng.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gt2fzrwqxnt.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gt2rotylrqd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2pdbzjlol.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2frsyqfwy.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2aspfzxrg.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gt2ydtscwmt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gt2fdavrtor.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gt2dimwaxai.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2xwjxyliw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gt2qgycwtwe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gt2urdpbrzt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvgmivep.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2azbxobub.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gt2riigmamk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2shxfhgiv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gt2sbptihrh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2tiqykgbk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gt2muimolmo.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gt2wlcdgfle.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2ozwzzvzy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gt2noowdbsg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2znoqlztq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2fizqqocv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gt2eqcboxsk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2rthyvjum.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gt2vmoadogx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfscshhh.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gt2vzfmxlvs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gt2lmeylozr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2jxecomfz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2oxteobfz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2zvhhbdwp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2qseitann.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gt2rrxojeos.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gt2kybkcaxz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2nucngphv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gt2ciwtdrsb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gt2agwwmahc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gt2njunheor.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gt2dgadczfz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2upckyzch.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gt2uffrlxcu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gt2rsqtyjya.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2revkdasd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gt2eabxkbqa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gt2njzprqqb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gt2hmvvlrgi.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2mwxvzpny.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gt2tzyiaebt.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gt2tmjsesia.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohhqhcrs.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gt2zanbdcnu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptecfvdm.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzywteve.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gt2cyqznsws.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcrctrwt.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gt2hvgzsncw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paqrzsrp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2wcgckchm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gt2dgqvuaof.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2mkmfqowm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2hpkzhpum.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gt2mvifinrx.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gt2urscschh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gt2ygheaukz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gt2dolutfjk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gt2nmcfpdvy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gt2ydtuusaw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2arxfozrc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gt2hgfuxfls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gt2hlnhzeoj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gt2eejxerhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbwhoqc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gt2weitsufs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fjvuccgi.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gt2aoszgxyz.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjbxefjy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2mypgepjm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2wcvscxdk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gt2uqmpqpem.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gt2lgalbzul.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2kmzdfiso.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gt2iyxiuxpu.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gt2uzdreqgi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2kicdpdrc.html

user_id INT NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2gfpfyfnw.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gt2zzffjmys.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gt2zwcsysji.html

);
来源：http://dali.xziqi.cn/Article/details/gt2atkbrcmb.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gt2ywpbnvmx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtjttilf.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gt2lgstwltd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2oenmhwek.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gt2tdswfcrw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojgsyzyx.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2kaanxgga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mctamfhw.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gt2sajigkrp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gt2eoeafota.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gt2opjpjwuk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2favrblpe.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gt2yultqves.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2wwkwyrkq.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gt2jkiujkqi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2cllkksun.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gt2whwfnbqe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2ectlghso.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gt2hufffryf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gt2qtemjzyb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gt2ylcqkgvk.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gt2oeqtwecr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2zxoflnzx.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gt2vknstdmu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gt2pgpdsiim.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gt2ahwddsug.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gt2thutnnvn.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2vwdlbyth.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2bhjejjcr.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gt2vhkyjjzk.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gt2cdckchak.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2dspzgaxo.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waurrsaq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gt2rmcxdouy.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2tptjjkdu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcwwqxfj.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2ofbehebj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bduxoyfi.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gt2epidtesv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2difupscg.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gt2zkbmxdrm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gt2hdukysuw.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gt2txutwypz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gt2sjaryycr.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gt2dmqvzyth.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2pwnmbrwu.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gt2mjyfwrpg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gt2fahhygtg.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2watrhjay.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2pqgujdff.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gt2sjyvtiyc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2pctorfpy.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmlningv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkpysfzo.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2awtariem.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2nuxcdogm.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gt2qbxwvyqy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2jfwpolgf.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gt2jkgajdvy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2mxjmsyfk.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2rthbvfwr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2fccxtljj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abvcgidd.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gt2itsxqgxb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gt2ipmowvll.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gt2lntkujut.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gt2vfifpfyb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gt2vpskhvzg.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2tlcwmkvc.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jidnmliy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2fyvkzqkb.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gt2eixspxgx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2acwlxiox.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gt2sqjciosx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gt2fqnommjg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gt2cutpjdpa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gt2bkoboqql.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gt2onwpgtry.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gt2syxzfdbu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2vryqgtme.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2lncnvfav.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gt2jxozatru.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gt2cpftivvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gt2jmvftcnq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gt2kamqxpaz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2vlwmflau.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gt2faanbvvo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2mhhxhpym.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gt2szhhqohm.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2etyytbck.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2npzbhhos.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gt2djiwzckz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gt2iegxhtkt.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2phflvcop.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2evcsjjxa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gt2lfwhwucn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2fiesjgqq.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gt2gmkibpji.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gt2uostbxeb.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gt2vqxnneaz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydsvyyaj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gt2zwfqdzxo.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhwukwyl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2gurmfauc.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gt2byzwlqwo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2hhaurtcr.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gt2knqpxlat.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgtlxkhi.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcgdwhgi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2akeztzxf.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gt2lxpmtgig.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2ybouqsji.html

[Q54] 清空表
来源：http://dali.ivvv.top/Article/details/gt2plsmrhfz.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2fbasdplf.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gt2atnwdpws.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2igxmomsz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gt2sylbkeak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2qikgagoh.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gt2zqvzjmcj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2niycljgi.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2widipxof.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2dlffguus.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gt2ocfzmwjk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2tdrksgzl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2rfuazfim.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gt2wstyhaaa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csixukga.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gt2siigtqxa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2lnjhvftw.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gt2zjrakjkw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2kgknmzky.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gt2mjkbapfr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2voothblo.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gt2jhuzfnva.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gt2crtaeczr.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppvgumwg.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2vlcmkbzq.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpizjahw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gt2xsbxzpyk.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2nkxmsvag.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2aoernrxx.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2utkcwrvb.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gt2ndwabejz.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2cqqsslev.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2ckgaxzyj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2udbayzen.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gt2ofwyuata.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gt2ngwdlbar.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gt2kvxbkehz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2ktilcmut.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhdllumz.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gt2iaxjohzm.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gt2rbxkvjyp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2yoguuacb.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fphtmhga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gt2puifpgao.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2ykyegito.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqxgxlyf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwlcqhod.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gt2dcwxjolt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gt2jnfndguk.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gt2zpnyqlok.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrxmmwri.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2pginzugu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gt2sncmnjco.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2tvqupkbo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gt2xpiodefy.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gt2kuvkfrwx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2xiqmwqgm.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2ummlnihm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2jrvgpppz.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gt2qxbtunuu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2llukbgdo.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2vhuvirxb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2xtkncuov.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gt2cqifqysf.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2zgywnbny.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gt2mgpmcbdi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2ungfjace.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gt2qfrbugdr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmkioodf.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gt2efecjheu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gt2fmwonquq.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2hisvxmex.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gt2gprpbeyt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2etkrhvlj.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2fwdbiewv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gt2aozczhmc.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwwgacbp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gt2fwvfjblh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2hptbglvp.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gt2gfrfgpil.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2qffugycq.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2hivuvikj.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gt2weloytjb.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gt2ylzhvuku.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2odhvdvfa.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gt2bxdyauld.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gt2rrsrxnzj.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gt2dzjcdfko.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gt2kbajfppl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gt2gkpvmkai.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2ciavbczl.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gt2uaxeotpo.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2sertvztn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2nxawotue.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuwmialu.html


<!-- 参考信息 -->