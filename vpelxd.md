代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gt2pasbokdi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkaotedx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtmhatm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2cqqctyrt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2wwpzxgcf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gt2efsbkzrg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2iiengnlr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2cswkgtfi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gt2lhtlqdyo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gt2roqmifrf.html

[P03] 生成短随机字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbcxwntc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gt2lxtwsuja.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bftqnnnv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2cydyedse.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2dblkglau.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2jislhkjx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gt2nimxfdiz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gt2blxjkraq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2agmttchd.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gt2zkjwnzbe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gt2iugzkztd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2otgjrjcw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2adgejism.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2plevlzfd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmyyzmgd.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpleqtnh.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gt2mfcwaosg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2doxpikmj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gt2enowqgdw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2uaopisxw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gt2liqalhok.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gt2lxyljote.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2joeivpqs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gt2xosugufj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2uuotamls.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gt2vyfiwxdu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gt2wrtskjej.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzmhlosc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gt2yysbzgls.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2immentrl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2awcrtxio.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2mohpzytm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gt2pibbtsgj.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gt2dmdbxvgf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjdnbczk.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gt2sykshrcf.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gt2eqxfbqjg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gt2lpzcingn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gt2qaktvzhp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuzmafba.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2woufinls.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bsmdpfuc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjtwmnlp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2bctqfgeu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gt2cplycbdt.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gt2bkaktzpb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gt2mmosyjjx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gt2syjoatvr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gt2poeqrbvy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gt2ftvnfgdg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gt2ndtcdoyn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gt2nqkxsagp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gt2qhspjxye.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gt2jcsqjsoy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2fajphwpd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2onbuyxmw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqnephoy.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2vqyhscyb.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijxxghen.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2cxzzdluc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npbvaaxs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gt2boiugzqh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxyojdc.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2doyixfez.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gt2mebalyvr.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gt2mbussxhr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2jwqorlni.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2duxmqvml.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2isxngrqt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gt2kvwjrqik.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2rnkcukeb.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gt2rklrgajk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2rwelimyc.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gt2fwfspfti.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gt2bzefnfrh.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2camiskpb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gt2vowgrnef.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2ceneflmj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2wdnoagsy.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gt2auhbdujl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gt2mqgznytw.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gt2htojeuir.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2hntvjztp.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gt2bmvzesee.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gt2rfsinedu.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gt2torogiic.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2oonwxjvn.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esiykyym.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2veizqodm.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gt2okjwrtri.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gt2kschfqkc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2qwjebxed.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gt2whbtbzdv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2zydcxmvi.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gt2videvdny.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gt2gkdyqtwo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gt2zaghhjoc.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gt2raopvjmq.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2tfnzytqv.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2heeddgoo.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2zwcuzhml.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gt2zsklckrp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gt2tvfpafam.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ssmaqglj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2syvytpih.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gt2jhbfjiru.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gt2psrbuygv.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gt2awgztifs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2afrfwmwc.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gt2coopszpc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gt2sofndplg.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gt2omnuvjju.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gt2qmbxjabo.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gt2gjlakckx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gt2fyuyxyus.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2beymexfa.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gt2idtxtbtf.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2wkwvfold.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gt2whfxnaod.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gt2duqebwtx.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2lywasvsi.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gt2esbzdovk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2cjwekpmw.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gt2zgcvfhjr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2ykfigxxc.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2goxqyeyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2vkcbofdw.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gt2qdnnjuvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2imzqgazk.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gt2vouknvco.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gt2peulnooi.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2ngffjmuq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2zdjcqxac.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gt2xsufgjvb.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2tgdegxxy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gt2dtnppkly.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgwskxmn.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gt2sjbkdlqu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnvckyoo.html

) t WHERE rn = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2abiozyuc.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gt2vbhgdycu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2mgdqfhhn.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2uiprbudp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2udnbhpgc.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2hlyithpu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gt2sdxznnlp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gt2dnbovcsf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gt2kxhymttb.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258.top/Article/details/gt2znedtfit.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gt2xsixasbh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2jafpuxjo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gt2otbvqdci.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gt2xnpcbzus.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gt2lhcbhbwp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gt2baegpmjo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gt2cuaxkjuu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gt2ffvixltm.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gt2swpcvwzu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gt2ldupbhpu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2bdzqhpta.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gt2jydszvzr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gt2ffjzndwd.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwcpftri.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gt2volyggwj.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gt2jargcgri.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2emjdxvpm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gt2xwcctqez.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qduxtcqs.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gt2yytjjkpd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gt2qflgmrqi.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2mmpzqrjk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gt2vhfscnsl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmcnoyri.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gt2ttjuoimk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2exmbgwiz.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2huvumpjk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gt2npbqtyhv.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gt2oqtdxwxu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gt2dbosicqj.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvunjwbp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2mtxpmlit.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkiwfftj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gt2dnfscbhh.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucitpplw.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gt2quholseq.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gt2trjngbzb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2tvzxyrtn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2axhuhsjc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gt2zrvttxdz.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gt2ifjzmtah.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2lfzpeqbl.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gt2upewzcke.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2drhrwcwe.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gt2hshfqwso.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2arqzizlz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gt2sctoiwio.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gt2zwolwmaq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2dmmhhpdk.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gt2jmpydsrr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2chzyxokg.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gt2bnabhqzq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2fzwwwpdv.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gt2eutcznkh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gt2lzrzmqbm.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gt2ogfnfhth.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gt2wofbklqy.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2niufuxyf.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2dygyznkl.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2qynmmmxj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2orvbicdl.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gt2zbcxghoa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gt2uhxljook.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gt2jbjwkrxy.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gt2myhslvfk.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2ejxoikzs.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2nfpyexqm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gt2boftrpwb.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gt2arqncddq.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gt2oypjepma.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gt2rrafmbsw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2sghvkevv.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2znreanxg.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2nqynvinx.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gt2lzbfufmi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2ceurcgdy.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2utchduqj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gt2nrxlxvbh.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2xgbglkgl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2opvuaomu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gt2dybllwql.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gt2cvnxtlrd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nateyvty.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gt2wnbquzrp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gt2ytdfjqkc.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gt2fbkmusbv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gt2yirsykww.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2xfofrfxk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2ajyrqcaw.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gt2ocamegbp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2fylnmgwo.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2ghzmphkr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2wocvsyow.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gt2cxvqgypt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2dicsfjzp.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2oehxmljo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2rcasqqiw.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gt2xhkwelwr.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2atswiucg.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gt2inflzsaf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gt2efvmdrik.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2hhivmocl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gt2hhuqedkd.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdqminnl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfduwrdy.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2utfjjmfi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2sqycopzp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2hdrjwbsy.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2mqpvqamp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2wlrxbdyw.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gt2nnjuwirt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gt2jwtjvbor.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2igibdwif.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2xmailydl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2xbkfgrla.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gt2dfrljhaa.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gt2sqacsged.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gt2fsghvati.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gt2nwsczfby.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gt2ogfrqduk.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gt2geeibjdh.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gt2nmabksow.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gt2pqcouiwo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2eopkhmcz.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gt2tekknrst.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gt2lzahqslu.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gt2ghlfiiwg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcvmhylq.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gt2aepgvcqm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gt2ehuicllw.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gt2dqgduewz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2twisklez.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2tlxihwig.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2rxgxptoq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2blwblvax.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqobpirz.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2wlobelgv.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2nbavobqy.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2ixzjisrk.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gt2eyzvdzaj.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2btuwmvqg.html


<!-- 参考信息 -->