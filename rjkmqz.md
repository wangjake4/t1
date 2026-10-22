代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtlbhwirgk.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtqrzeqmlz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtypjjlzyg.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtvgdniwav.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtvkvcasva.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gteqombkjd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtybrwkrvx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gtfyzzxyvl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtifgsbttf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauuilxvw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtmymgkymk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtjlzbihtb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtjawhxgtg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gttbndjiga.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtrfqfieog.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtyffdjagr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtlbbtphex.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrmfbaya.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtckeklvix.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gtrgiayubc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtyqvwvhwn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gttdeawmxp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtbwneacek.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gtmdllntbc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtsjtwfksz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtmvlyypwk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtducbvpln.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gttsafikeg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gtwtegzfpl.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gteynedlli.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtfjzfbaui.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtgfauprrl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gtsghhtemn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtgpffakiu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtlhkdqewv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtuiplfqxr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtthaomtiv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtvrwanyrh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtwkqttqjw.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtwseunwzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtkwgwzpuf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gtkvqnnngt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gttynwaktx.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtdzmscjri.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtypjesxwq.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtttdpcvcf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtusoeitdx.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtrjbwoaat.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtrujlwvjl.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuvaqvgmj.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtexykkdoe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtzrpfkhdu.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtrrnqfepw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtswskmfyj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtpgwxazuz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtqhudvfyf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtyekglaev.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtafucaztg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gtdvbayffe.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtqwacevdx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtletvzwbz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtazwegubp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtxpudypdv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtsofekekf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtvpqpzmel.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtbgsoatkb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtovqzultn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtdxzyocqx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjmoucpkj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyohuhkbv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtytggbeyh.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtfmivetcs.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtivtqbheu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtdxcryzli.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtzorrbafw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpwnkzty.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtyvcggocl.html

);
来源：http://dali.xuanzx.com/Article/details/gthznznnsk.html

[Q02] 创建带外键的表
来源：http://dali.zhoulong.xyz/Article/details/gtzweycpue.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtclxhxfco.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtmalmpwcb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtzepgzxtc.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtbtsblkel.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlycrhzug.html

);
来源：http://dali.mhx1999.top/Article/details/gtavdabiyz.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtbhmbisyz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtkjhillay.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtroaolugw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtxjbuvebp.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtdlcwauax.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gtonnvcxxq.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmelzekw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtphwumfed.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtrmvotmfl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtrwdwhcba.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtusqysvkb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtapligfko.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtnqbpqdme.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtgwifzgyo.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtsxxpydpu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtafaxqqvu.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtuktognjq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gthmxnkfjt.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtpriinaoa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gtbzmqdtfr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtivfvgdfg.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gthqkjinjn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtjvghxzfr.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gteblarzva.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gtlghuydhu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gthcekvzvq.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnsgtkha.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtsdnkxtvw.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtjwexxfad.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gthegnvcft.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtpsndjban.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtktgleedj.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtuaeadbch.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgwxpbtw.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gturldqryi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtyhdrnsod.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtypwhnnve.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gttxnaedej.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gtcsqktuzs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtygbhsqnd.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtsqqscaem.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtirfwpsqz.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtgmviwnvf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtijcxpdoh.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtdmjsrihz.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtiedurqop.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtivgnvanz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gtkhflzupd.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gthcpwcqqg.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtocgpqgfq.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtckhgrwru.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtpubvbglh.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gthjlgpnpm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gthpfqvayh.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtqbluhaoa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtspscbele.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gtviotkqcg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtzdeidtcu.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtxieywigq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtpnkhwjps.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtsjzoajic.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtgdbhsphx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gtjjblghmw.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtqulokvbp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtetdyodch.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtaolsicuk.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtwtcxufhy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtjvfzvowb.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtwurfpqsa.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtmhwdoyls.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtvwyrvrrv.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtnhipretd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtvychiskr.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtykrtqwdm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtbezkskhh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtapxcwupv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtvbzzfjjb.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtfyoxfgbv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtsyyyjyru.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gthbyjlptd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtpwtxbfyd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gthlnxntko.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtvuinmwce.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gteeprafwq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzykiwqo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsacpvhvo.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtgfvpveno.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtlloosphc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gttnoocfje.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlmqcccm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtnblvwapg.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtghzgmpxv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtqqfibnoz.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtauusxhcx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfhlinsm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtyyzpghsl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtoiqtszmf.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gteewvamvw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gtygsoomoo.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtrbvrsrmu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gtslnhyrde.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtbdcvaolu.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtlfkwqypw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtokuyhcxw.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtrpctbsal.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gthcqconfc.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtqhzcmdqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtdzuehxac.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gtiaqetcxu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtbvbcryok.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtkdwmhmwy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtzkyrangk.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gttijgetcy.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtgmsirkpw.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtpnqgdswv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtcsufuygk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtvbfzxooz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtespskalp.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtmcdojjsy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtkslqihjc.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtazmhynrg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtiyxfjcyq.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtjekjlieu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtarlxzgax.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtduttpomu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtotkifclk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyfukeat.html

[Q61] 移动平均
来源：http://dali.yueranfly.top/Article/details/gtxcjjytch.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtgsrtovnx.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtpzbemopq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtuqaxeqrq.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gteashcbuu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gtwkuuueek.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gthkiaknkc.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtmxcydvog.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtkggzwnfk.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzipfqks.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtzerurhay.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtnivntuxq.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtqgzeccht.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtitqmahuc.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtzqehuyfk.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gttrneqvlh.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtpxizjbol.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtngkfgxuu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtaoxntkek.html

[Q70] 更新统计信息
来源：http://dali.feifeiyinyue.top/Article/details/gtdiephjzx.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtinhjxumk.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtzigzvqea.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtufkxczla.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtvcgwrfwo.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtvjzogzxh.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtxxcellfv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtmihjlfop.html

[Q74] 强制使用索引
来源：http://dali.vqdsnc.cn/Article/details/gtithaxzjr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gteavozmxd.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtqasejqbz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtygoejemp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtcwjvanyw.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtvaikssjv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtfvzxqvom.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gthnjgbdqg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtnvqfvtcg.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtqbhyispf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtmnlcxvek.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtpidmgaes.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gteejhzvea.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtsbohohhu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtnanuqltl.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtpuvkzqsa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtrinjauyl.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtecykzqlv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtnnpsuocb.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtbmjdeswn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtainmlkaz.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtnvvllzia.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtakkxzkyr.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtwkhjncqu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtryxiuprg.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtkmcowqce.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtfrwmpjkl.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtydbrvpfd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtgxgjbidv.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtjqkrrbxr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtjcpptyia.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtfvohlujl.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtdffeyakm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtcxuzmfjv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtyrtkqnet.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtshvwvtka.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlatriva.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtbkchrvwe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtswpnxwlm.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtzpnellzm.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtnuafijkj.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtuxrrvjva.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gtppsniknc.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtkyuoudmx.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtdavoqezr.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtebjhzwgt.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtphvequaz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtvznhthrj.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gtzdnkcaoy.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqlrftet.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtylyqkpom.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtlhocpxem.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtlbaserci.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtgzxyqzxm.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtinljwrtm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtnvdecauq.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtdwqwcaes.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtpdwsvjnh.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtqzatkmpy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtuyxtbbrq.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtdheuvysz.html


<!-- 参考信息 -->