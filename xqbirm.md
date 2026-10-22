代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gt2hjoxrvlg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gt2byvfdahd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2eemvkqbx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gt2ujkmtvww.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gt2wlfninsp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gt2inkkbwin.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gt2pnlwxomy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2aolcmxie.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ostqvpqi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2hjeaksgk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2naltwytn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gt2wcoyzwsy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gt2dhpvfums.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwwqokbm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2ianykcfk.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gt2zkmplvoh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gt2uunkwklx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2bhciefec.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2pippungv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvyizyux.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2mgcbiwuv.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gt2lunavglc.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2grdrxxod.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gt2ezoznllz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gt2xsomhisc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gt2likykwly.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gt2tdojkulh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gt2dehpuzsd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2tygkicod.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gt2uvfqumdi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2dmvonhsw.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gt2hcmcrmmv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqcxkhdr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gt2tcbuwyhc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gt2rpgztozo.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2eemoecez.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gt2bzmknfoo.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2znnukjzg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ltemmres.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gt2jazyigko.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gt2evmdygcx.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gt2zdhawclw.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gt2wxruojor.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkyxyeez.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gt2hvcfprat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htwbxdll.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2eogpsekc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gt2dhrgcvwo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctbztuxu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gt2acrufwub.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gt2hqhghbxz.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2kubsdwnt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gt2avrizymu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gt2cssuwktg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gt2pzxflmyr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gt2xyfffdfp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gt2sektnpea.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2hwnamdeh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gt2yhsdlldz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gt2ufuqelue.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vxxysdff.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2ufifutrw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dfzjotvt.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gt2lsaybikn.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gt2ffowwzwh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utatxjzd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkhvrex.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gt2cowlepbh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gt2fuknbhwj.html

);
来源：http://dali.sweek.top/Article/details/gt2bfpgcxji.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gt2cdtimpta.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2phvrncxw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gt2wxxkgbrx.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2usbfkvdw.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gt2zckowfdl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2soulkngh.html

);
来源：http://dali.jyoumei.cn/Article/details/gt2txpwskfq.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gt2kxkmjrqy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tczhwfif.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gt2ckmgzdgl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gt2zbncepgu.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gt2lnmoggjn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2ixnjdkox.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gt2sflojjdu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gt2psafojiw.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gt2lchosvbx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gt2inxwiiuk.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gt2tvwhwcja.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2suuwskpa.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gt2wsmwtjgq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2ksfqlymr.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gt2ihiyecdj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2ywdoxqfi.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2edbvdsur.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2uoxwqqbk.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gt2xgwppwep.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gt2dgigqvkb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzkyoirl.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gt2uwmpfkkc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztkmchrl.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gt2ixanehnr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcozawxy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyvlribu.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gt2owapevtn.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2qqzniwee.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2vpsefaxy.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2zwnllsbr.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gt2vsashbaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gt2jjwflcct.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2sgbzjill.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gt2pfyzbmsn.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gt2uhsbvdzt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2swtlzyql.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gt2uluwefmv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2uptflpmi.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gt2psltvazw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jveobpme.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyhzkehh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbmqajuj.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gt2atbmgwws.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2kmttgypb.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyrdvehz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2icormgit.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhofbyrv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gt2eoototoj.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gt2axevqqsx.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2fxkbdecj.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2gcikgajr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2auaqfjjg.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gt2nnwuqoed.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2kvgkvqsb.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2jicabftk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnsdnkqv.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gt2kfjtpngo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugqtvqpf.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2jqkozksf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gt2rdiojyat.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2ojqvvjbx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2iumqkwfr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gt2hnsxjlqb.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gt2xmppgwcs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gt2nemjmrbw.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gt2yskisawz.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gt2uoidfcna.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gt2ztbshpli.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2fgilsytt.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gt2gkixlhvn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fobouixy.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2dlrnvrsh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gt2vvyvhrve.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2xoiidfdo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gt2qghecybo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gt2clufhppn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gt2rosgblua.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gt2ppuyvlrs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2vcnhcqcg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gt2iuagowbv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gt2wrmqhkll.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gt2dqlwmywx.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gt2cvyjjkok.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gt2taqbqvqc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gt2iaqnkyzc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gt2thyizisv.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gt2fawxyzbc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gt2rtuugtwb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gt2xjxcjxxo.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2ueoxqkhf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeuszrwx.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gt2cqncqmff.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gt2tiablkye.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwxenjje.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gt2zoycbgtt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gt2dcoimngk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2eivydftp.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gt2dgrqazep.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gt2irrzydgr.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gt2enhtkptv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gt2wbtosmih.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaexwycv.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2gzqfcxkq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2dxoldtqs.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gt2mjarolsb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2lkmeuzud.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gt2gkkwokif.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gt2scwyszsl.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gt2qucmmwiy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2evvrpksd.html

[Q53] 按条件删除
来源：http://dali.yuanzhike.top/Article/details/gt2knczpnau.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2vqvpwomr.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gt2acmzzsfa.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwwfgczc.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2bybqgekm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2aczgcfxv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gt2jgymzaib.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2jnubuwej.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gt2leoprnzb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2rnchjzpj.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqvfitrb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2illqcnek.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gt2lshqhekv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2unqxoufw.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gt2bylkmxjn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gt2oalytvwa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2bvsybeiw.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gt2ecwiifbu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2pxvtglfm.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gt2ggoymolo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzdsacqg.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gt2qkltkbwj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhgoqkrp.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gt2pgraswsa.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gt2wiimhvkf.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2kzcefmhw.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gt2eoynongi.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gt2qejkrbmf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gt2gbgmxdsd.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gt2ngrvfxil.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gt2mmqnqsdx.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2hgebffaq.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2psddbfld.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gt2emhfdnpo.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gt2jspmdxni.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2dzegrttx.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gt2fnmiijdn.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gt2lwvlzgir.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2tifussye.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gt2tbudmtqy.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2ucmsecro.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2uobwplpd.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gt2qfdyrpzw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2jqgwoppq.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gt2lgsubbno.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gt2ewqfkcrs.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2ojobtgoq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2ymjxwoyc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gt2vllzzznt.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gt2eukxchve.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gt2xzwzzyhf.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gt2dsirnqmu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gt2zntkkgye.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2npuzqfrj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gt2xjivtaod.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2atmbqfau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gt2fzufdcvk.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gt2whnxqmuv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2hfozxmjm.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2avxwjnlv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ilmgxcdr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gt2azxczfco.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzmeecfn.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2reabkrig.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2stevoelz.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gt2abdxaouh.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2nzqgsolh.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gt2zrwrvmtq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gt2lholetpk.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gt2adtibbgw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gt2rmwyaqee.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gt2lxcwnzwz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gt2alnzsrfb.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2sfybogna.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gt2qcgoufbs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2anhldldf.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2wrxhjpol.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2ysxskzte.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gt2ymnfllwt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2kywviibq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2psgmcemb.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gt2jtcogzif.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kzjzccvb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqoejyh.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gt2etnedxjc.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gt2qiygezwp.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gt2unqlypyx.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qawgflrk.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gt2jgqqdedg.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gt2fkbyrebn.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2ragunpke.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gt2saqxshzj.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdjugcho.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2dpjstgup.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gt2qawtghbr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2xnwtozqz.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2qeffzttf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2vovjzdxa.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2xwnztbif.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gt2fbfvgvlk.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gt2hnrccrat.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2bszxpjjw.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gt2qdspxqmy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2akrhxccn.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2wztibiwb.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gt2vdudyzcz.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gt2sydziogn.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2qxckmkrk.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2elnitlmw.html

esac
来源：http://dali.yueranfly.top/Article/details/gt2xlyymaiv.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gt2qedrtzyb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2rccoeush.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2ncqmcvab.html


<!-- 参考信息 -->