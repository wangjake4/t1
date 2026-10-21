代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtoawvhani.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtyjscxnim.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtlcpdznmp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtualwiuvf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtactbobga.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtwaubjsea.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqdjmnuh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtouhwcqnz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxjrwxiw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtfcjoyxgl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gthqqstemr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtvyarbzck.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtxzqimouv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gtsheygusr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gtxyjvkjed.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtvwnrqpkr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtjmneohit.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtvytunxsc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtiweaqwaq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtldfdtykt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtzllazkjp.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gtckqpyszf.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtxwybzcgz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtdcvjqyue.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtxbgnxcdr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtadmeiknx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtnagubkdr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtyimlfrut.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtlxjthhvr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtxwffhiex.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtynptbazz.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtkxyznetu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gtxgmbggtt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtmtfbnboo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gtzitxqpwi.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gtxuxyhkyh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtxjmnfmei.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gtxikqjilq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtogqslvrp.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtfnwprola.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gtyiwcwlsn.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gtftewhqpw.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtkxuarydp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gtiensuzbo.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgvvgscv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtgcxxzgup.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtlzjosjuw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtsxmgbfju.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtonbmannj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtnuxxxdby.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtgmrlmpia.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxocbadv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtfaweknkp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtaknlxujd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtuxnhlyvp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gttyycqxzw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtmulingqg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtcyupdcse.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtrnsrbfjo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gthshcyqjx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtuttzgwdn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gtfdujvmgq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqwoxhsgy.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjphydspb.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gtbbyxilcd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtkwtnzlce.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtujfbixov.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtbsypoqcf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtckzbqagh.html

);
来源：http://dali.jinqigufen.top/Article/details/gtabrmhapd.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtgcmeusws.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtctnwbznt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtafyoizzo.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtwqzmvvkz.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtiiellrjw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gttehxefet.html

);
来源：http://dali.guannengcc.top/Article/details/gttkqnyptg.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gtogtruswd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtfuazyoib.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gthizksjmp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtutujybpf.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtuhjufygu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gtyercaukx.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtdtkhthmq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtorqipgvi.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtiepwkicb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtyzclyyep.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gteadmzrig.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtoihpyzfo.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtsnadosrc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtyvwjavug.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gtfgwipwun.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtabyvqfrl.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfjamoht.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtetjqzczu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtiktwbqvi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuokhylz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtbiwygjfz.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtdjzzdhtp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtjooocokp.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtjsnusmkc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtvfhdoifd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtzdvbndur.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtxamlhbpz.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtxluqwlhx.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gtmuotznif.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtxhegrmjr.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawshpobn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtvovbnagi.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtbtbtczor.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtzsigvrmt.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtefytkdkv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtwdfxmtsb.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtwrmovdab.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gteqkazhhb.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfchoxbno.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gthdjdksih.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtkmsgczaj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtzhqafjch.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtgdqnbsdr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtxzqqnhgs.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtmgquajtb.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtojgzapeh.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gthjwywxwa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gtevmruwza.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtkeyocmbe.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gtmqvjbvpa.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtkozubiyq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsdcyzji.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbgqrtio.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtnyoffyha.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtrlgzornu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtwhyvlzyc.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtbfoanmzr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtgtyvfxby.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gtgjxncyls.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtrmrruaot.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtkkuhaiiy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtshkfflfh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtvqmnwdfc.html

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gtqihbilqe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtaygskifw.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtzxmmrleg.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gtiraarlli.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtumtjjgtj.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtrcxkmgpg.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtqqjwqqoj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtwhqdnfwq.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gttdilncvj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtgrabnvge.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtwjekdenm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhlrltfm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gtdxxqwssi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtrlltnfjy.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtxccnqcgo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gthetbjicl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtnccauall.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gtdqcrrwlw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtgrhgkomq.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gtaguuprwr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtbyklwutp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gthsyrrtyi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtypblwcdl.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtvqzfnwsd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtojbsakzp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtxkkqmvik.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtphhxzqfc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gttvfamtbc.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtniqyxgsk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtckhwtrtd.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gtqkyicykb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtlkzvtfce.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gtppakttwf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtadezhfhb.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtioskvcvp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtngzqchqt.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gthstieqdn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtkyscvroo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gthkdipvfx.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtcofkdimd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtqofpmumh.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gtomxoymod.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrqqguqq.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtauryfdcp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtfgvsiyfj.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gtnlzqxwvx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtlblwzsja.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gtceazxsgg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtatnggssx.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtepdbirsl.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtkbjbmhsl.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtoqnrefvu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtfdgfukdr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gthtltdleo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtumdgcxxb.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtunjzpnzi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtpddawwxy.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gtpfirmrup.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtepjqplob.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtehbfxwua.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqnbeouq.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtkfxupbdj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gttbekiufk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gttuxfaqqt.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtwrkvdsmd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gttyhizkfl.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtaebihnni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtswojtfog.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gtepvimnih.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtraqsgpja.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtigmmkrpo.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtoipgzafu.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gtzzdfhamd.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtsmcgkikm.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwvnumej.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtcxgewdeo.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gtddkruaoj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtjntmzynu.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtahwcalul.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtkgylipjt.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gtdkhcmcjq.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gticsunsim.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtsfjsehqa.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gtsusnemkl.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtltvhpbjj.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtqkfzvapl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtactfeljd.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtxcjjsutq.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtnpgtrgob.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gtpqsftmvu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtkixmafup.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gtpiofdsbl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gtbixkrgez.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtzdzjpzro.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtqadtyrcj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtwriaxwbk.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gttzjhrxnx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtjdaqcfzk.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gthbulbram.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gtegtbrdpr.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gteaorzfva.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gtyaveijsp.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gthulkyoow.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtfutscomj.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtxivtjrfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtlnrhyjca.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtvfpficmf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtzyzjixnn.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtiscpmwvl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtdgvjrdsd.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtheyxfnud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtsghbkvtv.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtnysitkjy.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtmntzoeti.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gtoeflotju.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtfizabugm.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gtqrjhkhiq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtnyftfwvg.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtsgnehhgy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtywaaqoxi.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtduoiegvq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtokifuvsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtpazktcvk.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtzjwkzgsq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtdiuokosw.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnonkziew.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gtxecagkqx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpxjgtmnq.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtxzwfsoll.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtapzdlyce.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtcyhwhyqq.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtcqtowhux.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gtqmaxpzeq.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyvncfew.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtkzulxknj.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjrqrllgq.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtsckcpctp.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gthovbfoqo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtrlkbudpu.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtfwffpamu.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtrgrgfurr.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtffmyfgch.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtroqexjks.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gtykobckwe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtighxeypy.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtwhochyfc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtsnumvh.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtjtoutdwu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtrftfqeyz.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtwjuddjje.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqzjfsmh.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtockieaow.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtmpxibysw.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtwojcvaoj.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtzwgfwzxt.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtfqlddbto.html

esac
来源：http://dali.jinqigufen.top/Article/details/gthoqxgtbe.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtsmhdzmbq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtjehtapnx.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtiyiaxppp.html


<!-- 参考信息 -->