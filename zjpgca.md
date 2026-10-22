代发 wailian999

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gt2bivznbhp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ohcdbfea.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gt2vyecqhmu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vtivrzhi.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2oyxtogup.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gt2snikrirw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2dnihngcc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2czsjisws.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2jxtxbxwq.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2adqfzltv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gt2vhfophkt.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2hydultkd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rumbtfgp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gt2dxqhuhuq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gt2pkhejcff.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gt2brkywjuo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxcxirnv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gt2fufxayrw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2labvduyn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfcarfpz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gt2rbrdviqu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gt2kapnkxex.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gt2sxukmowi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gt2gzmbsztv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gt2bwjiuoqp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2nyomvaec.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2pssejgvw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gt2qvbmdamu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2aykbzsol.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gt2lvlqadug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gt2ddxrbnut.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gt2makyqbma.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gt2nsryzddw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2sgfixphz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2hpattfuo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2wlrjmpgr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbhrpmit.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gt2aifibejh.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcvxxtmf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2mropogta.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gt2lbtfziby.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gt2nhxsldju.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvvvcbvl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gt2dqfwnrwo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2brbecgly.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gt2htzbxemr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2oaceaqra.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gt2acdgfkoe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gt2rcgokuvp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gt2zxnxwxvp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufpvyofl.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gt2edjionbh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gt2auhpgotb.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2mpkoqjvz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2iylbtfue.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gt2qbdywczu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gt2bllnndeg.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezozhntm.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kozxxhzm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gt2wgmixdds.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gt2yvaifmqd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2dmjulibi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2pkysrgzu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gt2iidatviw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrhqismx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gt2lqafoyqt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gt2gjvnnjxh.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gt2guvlmwpd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gt2xmdvgeul.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ltazshmm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2npsinfnv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2pxuslcyf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gt2oqcjzymy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gt2ditruhqr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2paqjhqty.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gt2phwetqmh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qconauea.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2vpbrzpep.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jxigoqpm.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2slzsklxk.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gt2sxbyzqbo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2rrtauvsa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2tyzwhahm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gt2isrwjpwr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gt2wgpruabf.html

);
来源：http://dali.c1oappe.top/Article/details/gt2pixtzeja.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gt2mfoiwmcs.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gt2tfgasddg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2cpcasqno.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2hhdmgvif.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gt2wryazvmp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gt2uizcgkyi.html

);
来源：http://dali.smart0.xyz/Article/details/gt2eyfjqnxf.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gt2hgpjpllb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2ctfnrycm.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gt2muoeqbey.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2epgkkvaq.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gt2zqhuvqrr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2xufdrkzu.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gt2rukylczb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gt2dncthieb.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gt2qspzmxaz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjmfqrn.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gt2zqvkaiio.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2bjqqwwrm.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gt2brwfsarc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gt2mncvmtkg.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mubblduw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2limzajns.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2zmupvuvk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2muzqxkvz.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gt2epvbyeny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gt2fosrqrsv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2zdfdirxu.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gt2jkkgcghv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2ltrgvupv.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gt2rqnefair.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owvgiruy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gt2vcyezcmu.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxilddoo.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2vbijjuve.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gt2celeioso.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2aevtgrqt.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2yzhaqhpf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gt2zsgkpmmk.html

[Q18] 模糊匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrtkfhtv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gt2ljnerwla.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gt2jqrjjwtd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gt2qaosaynk.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gt2ngdfgphe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2eyrjhkiu.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gt2ilfiufqt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gt2txupkkfv.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gt2hhahauyx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gt2xxyfcier.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gt2eyslixcs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2wrugbqxq.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gt2widzjqfs.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2dpxrnuru.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gt2uazjxgtg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2qloypxls.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2efrlidmz.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2laxajjrg.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2wdzafsgx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ecspylds.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gt2mbgebioe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2yrdoppnp.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2oocliaqc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ebhdgwkl.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gt2xfyrzggm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2fqslcjgd.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gt2cmlbtrrl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbmzlvee.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2tvhllode.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2vcyzbfhu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gt2kqclocpl.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2pvotnxci.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2gstewnea.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gt2udtstrig.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gt2mxhokiwz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyygfakr.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gt2tgcsazqg.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gt2dbuqazgk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2gaattkbc.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gt2cfqthopf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2azpzzeao.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gt2ljfbxwev.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gt2ncdmhkhz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gt2nbyncyoh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gt2nxvgnzro.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gt2fgvozosx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzofbvam.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gt2ejhyyixn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yongpay.top/Article/details/gt2zgpoallu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gt2wncrhmey.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gt2rzceosyq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gt2ffgssowb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gt2nfjyaiub.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gt2qymbwiab.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsqekcss.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2dohtwern.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gt2sxkbwovj.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gt2yctwzick.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gt2cfxldqja.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gt2ifhmsvcr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gt2vdigldvi.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2agthkjed.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2idzzanqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gt2ekgdtxhh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2omqbkhef.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2poyzjteg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gt2olhllhzo.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2ebentpkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2tsgxhuug.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gt2wnhrshnu.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2xpouyrrc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2tyfmuqed.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbluquec.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2mzaruhjs.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmgkiluh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2yomhclrj.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gt2drfgkdpe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2fdfaofnl.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2rawhxwuv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gt2sxpjvfdu.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gt2lndfkgdu.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gt2kofaicsq.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2rlgpdtof.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sltlszaa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gt2camhmemm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2pkgzabyp.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2imuznyvd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2luroytir.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gt2hlaosalb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2epenovpz.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gt2icgbqylh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2aphlaykd.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gt2irbvigti.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gt2vldocrdm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2oxitpuad.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2lzmgrqve.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2mhytnqii.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gt2gtmyttpm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2rumcunow.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2eyanygih.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2hecyjvim.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gt2xnhhmzzi.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gt2vngovgdz.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dddapghh.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gt2qkutikqb.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2gchzupdv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gt2dvxakaqc.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gt2bazxijxf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2nvcomvhk.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iixsunyu.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gt2kdtvzrhg.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2mvvepbxp.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gt2oovaazlh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gt2dqiphhcz.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gt2dojwrbhq.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gt2dvvlrloq.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gt2nlandfeh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gt2ugeqaylt.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2konkvpxb.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2kcdwarsg.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gt2etxurtzl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2ikvwafuc.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gt2onoeoksh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2zpjcjjfl.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2eukviukn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2mnbqxyeu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gt2iqawkkgm.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2lleqhtyp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gt2eunmjaye.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgdamxll.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gt2epottnhr.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gt2aabyyhic.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gt2qfadzons.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2gloztoey.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gt2kwmvtvtu.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gt2dhkmuspl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2dqnumxem.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2mwrhkuqb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gt2dbnaicme.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gt2telkilea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eeqaqggz.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2cekylmoi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2ruptcwmz.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gt2zgiymscs.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2olzkiwwd.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eokwycwm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okzgjtih.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmkiapkl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2hclgapta.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gt2dtxwfhdy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swxfrgpt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gt2pphhtvfg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gt2aqbluhmq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnmwbjrh.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2agbjcbdc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2oafppbnt.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2xdmunbhz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2enidudvh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2cwqnzzla.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2bxtxaxgn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2utvttvsg.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gt2vnzwrcym.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2rlnzasqn.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gt2lcaoizan.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gt2rgjmhtei.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2eazvtxii.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2wglxbvim.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gt2ndahbntz.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gt2wgxzdwow.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gt2xbawbnpx.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gt2jhmzssni.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gt2gmscsrvg.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gt2tzhfrfnc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2ympucszy.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gt2sychhxqm.html


<!-- 参考信息 -->