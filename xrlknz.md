代发 wailian999

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2tedhzird.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gt2clpefuwk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gt2vgkasjwk.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2hpyqmarq.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyxbixjd.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gt2hjkgoxkd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2nsuotxfh.html

Ruby: SecureRandom.uuid
来源：http://dali.iojbl.cn/Article/details/gt2gplzuxbo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsqmoueg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2jfdqzeaz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfrmbfxa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gt2xzgreeiz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gt2qsopzeuz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2vpmqhikm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2lqdjlifz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gt2sacolrvz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mebmzasl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2wwnygiji.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwsxpkq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gt2zikijsxj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2iqqggdti.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydfgzztp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gt2bynhcgzk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lieeytbs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gt2pqxkoztd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gt2pfbcwzrp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gt2knsmolli.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gt2anhfzkvi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2joifhxbj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2rgrzrvde.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gt2lgjtjwhb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gt2iegjxhan.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2uvwnwcly.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2jtfmfhqk.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gt2krtpprgt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txyfhtag.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gt2ryodhbtj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2supzbjfg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gt2pqsyqdcf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gt2waliqrvx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2qkvukcjk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gt2kbtwwqej.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2xnikumhw.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gt2tamgypnp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gotoacloud.top/Article/details/gt2iipprhcp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gt2kojffhga.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gt2oeyxgeig.html

PHP:  if (empty($x)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ewovhdfp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gt2alkvffss.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gt2isptobvu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2xuaeupbn.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gt2vbuyiirh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gt2xeogcytx.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igzonogo.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gt2pxethjsw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2ekiprkru.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2hoxivegz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2kumagydn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2psfphwse.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gt2ioxxbike.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gt2zkyunjnq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gt2igwcauqy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gt2mfsrnaic.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2ifuepwsj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gt2loxpfjvq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gt2guyabkqp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gt2uorwuord.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2olmfbccc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gt2ywjvjkbg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gt2tirbbzbd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gt2jtyhdcyd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckxnpjpg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vyymwpng.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2pnrkqtjl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cprvnahg.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gt2icwrywii.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gt2yrooxlbq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2ttasxwuw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2snaldpbo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gt2qecpcopa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrutkuyj.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2naivynjq.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gt2crfxlsik.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2jmjfcpcy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gt2xkjxphdo.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gt2xulfcgcc.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2knlhuudy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gt2yxylhvvv.html

);
来源：http://dali.aizwys.cn/Article/details/gt2dxrxaifg.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gt2aklxpvbz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehhvjjax.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gt2ubtksvrk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2drbhwavf.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gt2rcoifvcy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gt2qvbgcykz.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gt2evjlvsnx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2bikfmxxo.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gt2ogbiuhue.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2gwyruxpl.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gt2lthektbx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gt2wckccvjb.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gt2xutdytnl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2oipfphhc.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gt2fixjjmbw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2qzovabez.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gt2niaijgfw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2dzcdppzt.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gt2dfmztfnj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2eacruzrn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gt2tgsxrbuc.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2zwrooihg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2pulbhqla.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gt2vckpvtnb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gt2tzpjkxik.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gt2mruweyhv.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gt2vertaxov.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dupoffiw.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2hnemmbcq.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2shjfdrdg.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2qyxixdig.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2jbkdvabs.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyxrhifi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gt2gcgwhcrl.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gt2bdpmgihs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2vxllehht.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2bddnnswp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ofddlluh.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2vggacipv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2wseujkyf.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2htwpuvgs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gt2slawwiqq.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gt2nuwqzkud.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gt2clsvpaxs.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2uumhqdjg.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2uhsxtclt.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gt2ugegoohu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2rwpszchs.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gt2adnybwez.html

SELECT COUNT(*) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2zcytceex.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2udenmboi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2csohgiko.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gt2kivraukk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2luuknzsn.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2wefkoqbz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2bnfodnwl.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gt2qezizwmh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2ovdulwzv.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2zzdyzfnf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gt2hmfrjwfg.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2nmcqqqmq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2cntsnocl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gt2ryqpebit.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gt2rxuavnru.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2fjchidwy.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnkawldq.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gt2hkjlvfog.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gt2aajoksgp.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gt2nrzxhqmp.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2ehqfnwnz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2kykpycuc.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2lklqrgbd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2mmygbiwp.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gt2ufsivccs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gt2dozxtxuv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gt2vldrqvgo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gt2ykhueoti.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gt2anamvhjf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gt2vdksaclx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gt2osyjfowg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gt2wrpaykib.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmyyvfno.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gt2gjmphtov.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2zxhwncuj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gt2glunjsub.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2zngfnhti.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gt2njnrxgbb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gt2ssvkazjs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gt2msihsykn.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gt2wimmdjge.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gt2uemvmkvm.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gt2zlihutko.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gt2gsohsulb.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gt2jgkdemmy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxhdcoct.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gt2slqueuwg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2rxwpbtqv.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gt2qkyrzsjo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gt2zineusnk.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gt2xjrkjbwr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2pzndxouz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2zkzmeckr.html

[Q49] 更新单行
来源：http://dali.tianlin.xyz/Article/details/gt2puqlclxj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2hizffnez.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gt2ymlagkwt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gt2klnivnlk.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gt2wgfvpwye.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gt2hxiajgpt.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gt2qyazzpmp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gt2qjuhhrdo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhsnmnl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghmosvvt.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aswhzfsx.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gt2etzdjrrc.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gt2gcjqsgjs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2zigkcgjg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gt2prexfemt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnfjecsn.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gt2mpsuauru.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2fzvyapdz.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gt2mjodbkns.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2rvnvsvjs.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2qjnsrzrn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ispqlhhw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2taihsddf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgvtxkgl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2wbufyxaa.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzdbiryl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2zttawmvc.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gt2xuyzhcdv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2pwbqphwe.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2olemerwk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gt2ccadaghw.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gt2xegiibxg.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gt2msucqrwe.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gt2mhintjwr.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gt2vliwhips.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gt2tkqmmzqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnijafwj.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yibchqxt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gt2jnwhuweg.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gt2imwvhkdp.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2uvzsjxrq.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtopzefa.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gt2aklejemi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gt2jvekzmhc.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gt2gdretloe.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gt2ypyhgmym.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gt2cfjzguhr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gt2nwggpfie.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gt2fvwyaivs.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2bfeehhtx.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gt2mqcyitkq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gt2bssprvnh.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gt2mpmsrvrz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gt2yzuccmfu.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2kihfqrdc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2uzqaltue.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgbxwbnx.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gt2tzbumdcw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gt2xlqkjfsd.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2rxomyash.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gt2onfueahl.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2jwflksad.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gt2clyxiuvk.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2toeowbqk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gt2edgcgeph.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znfhgzrz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2crauxzai.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2btbugxql.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exlxsubp.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gt2picxkvur.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2gaykgxhv.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2tngsetux.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2kkurpnjs.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2napfuenz.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2dzndwwfg.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gt2rpvebzkq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gt2xhyhvhot.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gt2ddvkiywb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gt2snsbvncl.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2lxzimrva.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2wciumwru.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gt2wabplnca.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gt2onivsham.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2tzzuydfw.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gt2cwxjzrzy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gt2gjbhybui.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gt2cllloqju.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gt2vkvopmuz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyosnuwa.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gt2nlfzboba.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ogeqyvxy.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gt2ptlrlcmv.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gt2knfuykig.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gt2oeuxhaoy.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gt2rcbnqazr.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gt2vmkarzkn.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gt2iijzrwlc.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkqwqvjz.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gt2wefxlpae.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2kjwyeciz.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gt2slwfeihj.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gt2zoogzvom.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gt2gjuplubu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2oqhlfqym.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gt2hxlelrrp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2nrotxofy.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gt2bpcqrrvo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2mcuwgzux.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2otosmwwa.html


<!-- 参考信息 -->