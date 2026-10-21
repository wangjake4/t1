代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtkknowmyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtmjxjamso.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtypjbsezf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtookpmpvw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gtdislufac.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtgvyegtsg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtqbidlrkb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtetuitndw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gteqiiczug.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtzpkwguey.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtvwvbiqjr.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtkfqqamzf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtvpaqkbzm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gturnuqjva.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtqjqnbyqu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gttrpsrrnd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtmuiuvvoj.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtjvxnwpbj.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtfindlwef.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtxixofqmt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gtrghkahkg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtgnquermh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtqrjdujzu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtllfrxfjb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gthgfutelf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphbpnhpb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtvamzkvcg.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtjficqbpw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtrewtazvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtbbvxawus.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtywfrdrzz.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gtobtyboit.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtlekhfunw.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtpjgtxsok.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtsjkkkzpw.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtygtahtch.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtwfcbkqhj.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdhkacdzo.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtjlljkchj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtaqpbrnuy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtejqkbwai.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gthckpijaj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtpszunydo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gtanwnrcds.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gttsnpqvks.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtxrpeklul.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtjwzzzusa.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtomqaclca.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gtepxevcfo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtrpsgmwck.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gtukiscnyq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtclozoapr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gthnddnruy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtauqgxycy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gthbzhaqlm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtwzmqvked.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gteovyyaej.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gtiywfzytk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdyfabceh.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgdovayw.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gtvkvwysdz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtwhbueogk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtfywwzxpz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtvsalyeda.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gtxlltfluo.html

);
来源：http://dali.dashuyun.cn/Article/details/gttbdcdkdb.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtdbssotaw.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtmoaauugb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtuvudqfyy.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgovypkr.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtxipdtnuc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtolmwfavz.html

);
来源：http://dali.ivvv.top/Article/details/gtroymombw.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtcbdoxato.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtvytrqdwq.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtcacgqqad.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtzxntqtrf.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gtjkxluafk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtvflxrtwj.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtvnjbuykh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gttgiiebtg.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtclhupmcv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtgxqfgrut.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlynqjso.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtrmzsqlsr.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdygsdry.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtrsobweef.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gthpinxbkl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtyzcyrjre.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtjfivmcql.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtesuahijw.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtldxamtng.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtjjcuvdzf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gtanwxrlay.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gthvgslytv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtqdglxtar.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtwhbamnbf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gtpvabuddl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtzwcgxiqt.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtcxcaudfa.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqadzqqdi.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtxapjygge.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gtrxoksaal.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtzxgmucla.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtscntsxpl.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtgtmgqlhx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gthudzwrfb.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtfwukekwu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtidjbcmcg.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtbimyomvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtbshdnwyy.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcvmsruj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtptgwikug.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtzzxnlyfp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gthscnfoxq.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtfnearidc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtgprocmbd.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtlxqsulch.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtzqffbmny.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtjvannhdq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtgpowxijr.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtnynzdssu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwelgmgvh.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtqupuzesg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtjtnkxlur.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gttxqkgpuu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtmrfzikhl.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gthpgxhaqw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtkeruvzyn.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtozitscdt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtgcntqzen.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gttuimfwrw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtqxrpewlv.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtulucyoel.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvkrljpd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gtkfflbobw.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtltlvfqwy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtaddrcnas.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtewlpxndd.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtanclzbeg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gtnkgunafd.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtguybvxfb.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtioimeehd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtpjozuswh.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtqceetjur.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtjeuiixzl.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtjncxrqoz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gtiffixykx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gtqeasonmc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtspgzupjo.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtgjvkdhgs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtogoxkvng.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gthpvidkic.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gthefedahb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoseczcgp.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtmmhmmcas.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtuivwncay.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtdxlmwfwe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtyikoxzdk.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtklbpmgsn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtkcbmpefv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gtsiclkbxy.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtbccdamkm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gtshpprsur.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gtywkxljzs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtlqfbbbqc.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtbqjeahpw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtjstfrixo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtoacxpnqe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtiitauubc.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtpeuvoepe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtltbdonkc.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gtpoulqvis.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtmcdmqnfk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gtgeryqdmy.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbikaypv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtlfujumwh.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtgoonilex.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtmajnbvhl.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtvxqfduqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gthcyiwzbv.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gtpiphdshn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtfrnjnkhr.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtwtyktqkm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gtlwqjnkkg.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtixdibapi.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtfvrlznfk.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtnzpcidzz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtkgpjsrqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtrtqjexes.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtuwprvsta.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gttjubgsko.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtuoxgvbvo.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gtafylmuoy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtecumsjry.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtelquumxd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gthsjtiuqi.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gthdgnluyj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gttkwrsdbu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtrordxmdi.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtfuchqann.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtujeiwwyw.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtonqspqrz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtjsbrlofb.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gtiuygprgg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjwhjnko.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtiryojbeq.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtqhtistod.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtstlwykpx.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtlnjosvoh.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gtjivryfhh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gteldgheyw.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtjratocev.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtvnjvuzqk.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtynlnxflv.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtzwsdtyff.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtnyazgizm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtfkgihbaj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtiiowfdby.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtvmjlyqfo.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtgxxswour.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtldilwqpp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtoufcgcnh.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtepthnqbm.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmywbhfyz.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gteazkhpqx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtcszctiey.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtnjrodskw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtutvqeyli.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtkrgxecjw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gthwlafods.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetxsbykc.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtvwvnfoxj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gterjdpkbf.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtzwpficck.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gthxcnmnpz.html

[Q78] 当前时间
来源：http://dali.pycfn.com/Article/details/gtoncyedlg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtnzjvnrku.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gttxvrvsle.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtsjaqmnef.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtpkrgpnnp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtukmclyya.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlofkwgid.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tanke756.top/Article/details/gtwwwmtfes.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gttoqbvfxg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtwvpvvavz.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtelrymldy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gttmftlpnf.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtfboymxme.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtttmlcrms.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtgicwaqsp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gtqumezxqk.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtmdzqjnxs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtgpzqxhgu.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtqbazxojv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtkqlxkgoz.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtpjserxvt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtreocretv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtvqtkswpc.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gtvnfujsnc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtnkifyzrp.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtcqsdimna.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtevnxsaxa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjeokvaff.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtjrbrorxw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfmkcuode.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtupjxpjrj.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gthaulqhch.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gtwztnhbuo.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtokeuqrji.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtmgsdxmsk.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gtpsydtujc.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtouesvymw.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtcvevjhto.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtyviiczlr.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtdysobdoz.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtcjpcuedm.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtainvvefh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtizfyynbi.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtvkvjtknd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtdjkoipks.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtbdrkpvkb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtramsijxy.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtqsprxwfi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtvmiptchh.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtislqoizl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtavgkmqkm.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtjxswvggy.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtbkpmwrsc.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtdurznhki.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gttgabzbop.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtefwgmskg.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtfbqfpesx.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaucflisd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtnnxepcdr.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtczdpqxud.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtrallymux.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtvdwnnimr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtxugzopqj.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtvjpaxcuh.html


<!-- 参考信息 -->