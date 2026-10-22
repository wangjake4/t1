代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdwtqjai.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtrhxpkxvq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtngqzgfid.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtfrfcntbr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gttjkivydk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cqqwz.cn/Article/details/gtslcfioye.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgpqvkbg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtytlmeixu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtfywaxueq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gteqpehbso.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtgfldzqav.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gtzajxomoi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtldzhjzok.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtyxutrwuu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtgogbpmbo.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtwcxktxyi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtcrltpxla.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtvtdxmqdf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtpdajukzc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtjmicyozi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtrdgoinul.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtjhspszda.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gththprzom.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtyfmcuqth.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtjonxibdf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtcfzowhgn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gtbkdtepvc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvkhzoml.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtxxbtlqcu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtwrtycxxz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtmibcrarf.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtftngogmd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtuzjnpuft.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gtbufgmjae.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtxwwtsnuo.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtufwfdhbk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gtlswscesh.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtvplzyzeb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtbdjlquok.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gtqypcycvw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtaruhytce.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgvarbxg.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyqxajhv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gtqnhnvqdh.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtvsqoqjvl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtxuhtyert.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtzwgbzeky.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtwxkberaj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gthbgjdear.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtfersvqwj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtrdoddwqt.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtsfxbncky.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gtxfkvhnzc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gtfbufbubu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gtgbtluemw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqrblicc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtcavzxzvb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258888.top/Article/details/gtayfylraq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtjcyfxnau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtrpardjyo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtknlrtbio.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gttcywhukt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gteyoddivw.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gttjmjaqsi.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gttqjljkbh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtoyhijpbb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtqjpjtovm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtgusmnkix.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtymjbmdgi.html

);
来源：http://dali.gzhubu.top/Article/details/gtevoqeouk.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvkzzqgs.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtczcpxcei.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtbqoxquqi.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtkopqkihe.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtvdmvmakb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtvwwpisnd.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtxmhgzhui.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsonakzb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gttijiwgem.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtmysfqszd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtbmnirkeu.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtsxzjqysp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtbvcyrnop.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtwcaovrjp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtravdimwk.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtingwhkst.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gtvdcinrtm.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtggydbyyq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtdduvatgg.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtgvruzueq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtbcmgjptw.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtokghxbxl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtxkshexin.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtoixmfxze.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gtdalmywmt.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtoaxefcrz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtnqqqeega.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmeandjs.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtkxzsjpyd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtxmhbqjir.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtcyftfzjj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gtivltaoeh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtqkfzxvcx.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtzjuxdtqk.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtcxfqgszd.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gteaxhwzps.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtncabnmeb.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtumlnrcjf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtszgxqinx.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gteltussmh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gthvyzwgrx.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtgwjpsktj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtwwxzokmd.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gtzblrzpoj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtoifjjcxt.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtjmaasdyc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtnzsglxul.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtceozmetl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtjbphnofv.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbnwpypa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtcayyxmaz.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtsrebtllu.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtbonatudc.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtqanuckuv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtazdynceb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtywxkedrr.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtqbzqoxfh.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtiodxvklh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gtpfknuxnw.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gtpzvblakk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtuqlsqpci.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gtxclhdoqp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbhkseyvf.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivddcxme.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtfveguubf.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gttwfmigxt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtcxzxxfho.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtdxhmhiba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtkgxsqwnh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtphhihpqj.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtimagxtkv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtrnflltum.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtvashpvoi.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtghiijbry.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtspcvburj.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gtrlikwtxe.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gtgvqolsub.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtgrswovex.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtbdiwzazg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtyutaaylw.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gtyiqrevus.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfktndqh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtocatdjvq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtjakvkhqd.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtvyzjoxos.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtscvbkklh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gtqxmsayjy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtcbvqmlae.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtgckjdokv.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtvkhgmlct.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gthekwrmud.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gtgzzwaiud.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtptmmroxb.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtmxtqiffb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gtsylbrwla.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gtqzejunde.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtbyroypau.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtbjuwcyji.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gtffuhhdtr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtreoveiwi.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtfszledbb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtwcvebake.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoykzvatc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtkadnchdz.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gthplpkosa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtwgucumgb.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtxbaigkdf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtumjzosbe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtzkwdiaxt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtmvsbcjqi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtfzfdydsw.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gteweahdmh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtpnopruix.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmztgmdm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtoxkidgmj.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtiyzwjais.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtnmppubaa.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtrjjapaqx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtukmuxnbm.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtlerfrgfg.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtuxtaicbb.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gtvfsrowhz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gthtruoprc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtevwdogsi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtjeisasjk.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtgfqojopi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtddfufgel.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtxtpxfcok.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtaqpomhec.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtlmdakcsq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtpyxtqvwj.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtyjosphil.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxudjgmm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtmkpgnlvk.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gttohzfnkt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtgfyflpjo.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtupkcxtud.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtipdeipsq.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gtrnkngckv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gthxymklql.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gtaryfaoup.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtpetfeiry.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtisixtmzg.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtleeeiauk.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gtszquvptd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtnmzpaxmo.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtguwczuqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gteqiahevf.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtafodncpv.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtkhjfqyvu.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gteojmkajg.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtjxuquqrm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtmmvwdvma.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtzjbrcmvk.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtsrslurxm.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtteodrpyv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtyhmbckip.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtmgppites.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtkywywokp.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtrxoajyrr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtbaacjvdl.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gtwsgfpfpc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gtagirmyne.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtnekrfgjd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gthqysqbcd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtgzyivefv.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtaugfvohb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtokhojhpy.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtefzqvrcf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtmntebwep.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gtazjfwufz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtyunghrlr.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtgeibbgpr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gticxhqxzx.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtswhrpjjo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtxfcqlrnq.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtmyxlbchw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtxqrgqtcy.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gtivqrlxsg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtldsykpjp.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtvtsosyvc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdpzedfd.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtnqfebnjc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtbajqssal.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtjuhakews.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtnggsdbnx.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gtiiarokoa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gtzsqvvszt.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtubsguciz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtaxifxsxi.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtpqfueiov.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzgdfcpy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtduytchaf.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtzkiwxnxu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gtogpyugmo.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gthhgzixrb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtohepowle.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcbvehpxa.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtukzxhhar.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtyiqzxmtb.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtztwztxdo.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtawbczfqb.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpgxjivf.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtokvhibts.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gtbgxnhury.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtgicdxuqp.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtrnrqkpxy.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gttqsixdvw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtilesovdo.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtclddaqbd.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtrsmpkldk.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gttgrjelxx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtmlblksub.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtfmhdqmiz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gthkteauvi.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtajfjzqwy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtakkgmron.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gttqcdetgl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gtoqntzska.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtxfzgwnvk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtgovbywmu.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtfsjfmbli.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaqmjwmc.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gtuatgaqgs.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtzvibsmtg.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxntzkhsb.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgyfstyf.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gteqklztfe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtapkfzkvg.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gttdglvbhc.html


<!-- 参考信息 -->