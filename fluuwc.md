代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtrgclhlje.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gtkaafrrvc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gtjvvxjndi.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtepqpfcmh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gteqnrodrg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gtrlrsizde.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jlsjyb.cn/Article/details/gtquavbasf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gtmwgggbnc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxmrgzda.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtjnaeoqjh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gtbzhdacqq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtopyqxlyk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdzobqwiy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtvpzoykpz.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gtiiagzfyv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gtwqpeulpy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtnephbqnw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtjwklzlmu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtmhefetsa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gtjizrsljs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gtnabmkhfq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gtqtuvoeks.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtmihevsqe.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtgbttbqln.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtjeocderh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtlpzyirhi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtnwqhlycv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtelxjznjr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtqqgghyhn.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtkdxasbvk.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gttpzbujgu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtidzghklb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtncfqfsxy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtnmtaxjjt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtsmhmvvwd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtedlepycy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtjrgajmhj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gttkwhhvjc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtrtbuqvli.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtqqwqcmyt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gtjbhlhbgz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtdlcbdqtj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtwrdkavoq.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtwfzyorxi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtkzkxtlra.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtdqearbvt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gthiqspxsf.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gtfcjqzcba.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtkpdjexru.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtgyvfbpit.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtnppftycy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtkauhhtyz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gtitvwdhuz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtzeeemadb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtulkrzfqt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gtayjomziu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtpzbcwxwe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtjsejsdxo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtqyhpzwxd.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtmfpbcqqn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtnjoudjaf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtompazqvq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtplsrjsct.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gthfomplqo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gtojhwwosg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtzzmpskja.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gtofycrfyn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtvxkpddwi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzyjlaxgj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtwdusuild.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqlzxrsfs.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gtpgtzfsmi.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gtpgigabyv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmamndiu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtsrsndmrl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gtqrdijtjo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtwldudyfo.html

);
来源：http://dali.haohaochexian.top/Article/details/gtanhsxhzm.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtxfedcwvg.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gtxhzwspct.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtoqhwibhe.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtqgcauaam.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gticmvkpad.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gtfnpzechu.html

);
来源：http://dali.nanxinkj.top/Article/details/gtaqsbaaif.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtlounnjku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gtzyqdwwey.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtbyxmzrvx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtelftyfht.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtcxqaunuu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtgfyqpmll.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtoyzcwpha.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gtdigmnfid.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtohmcwzem.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtdkwstjid.html

[Q08] 创建普通索引
来源：http://dali.jqgufenzy.top/Article/details/gtibgvgbyp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtfnwlhyfl.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gtruxjsmvy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtxbqzdxag.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gthpzwleog.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtwvptawaf.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtkzunshae.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtiimyjncp.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gtdozjlaaf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gtmeexfbkw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtuylxixco.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtljizebji.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gttykotdlr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtdwjvrzvr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtkpqbcedu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtettvvhlw.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gtnvkqgghi.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gtkviumakv.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtunbhjnjw.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtygvsxyaj.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtvlempoku.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtjehrhfrh.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtdhxdlpjr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtaaamkyxh.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtsvawrqoe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtvdafafsm.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gtanrghein.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gttnwnuzji.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtjccrhjtw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtpqkxxzwi.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gtdvfauvpk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtdkxwoojo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtpdwplbyk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtovroszpk.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtrkademvi.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvmnjapht.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gtuuyyfzlo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gtoiqtokba.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtmcpmcpib.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtjnujzwft.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gteshbggkf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtgdidedht.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtptkjepyb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtavodiwxf.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtzuppqdhq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtsjbvijre.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtmkiqatrc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtjpjweaii.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtbfkytjyr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gttlzllrqm.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtokebwcdv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtslwiqkml.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtyfziovxl.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gthqvfufhx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkjgfmku.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gtlymkbsdw.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gteshfkxor.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gtyromyhyq.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtyeemiszt.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtlbvhdumt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtothdkjuh.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gteisnmqzx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtbafajksa.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtvhfldytc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtdvfpjxaa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtzrzcvvkf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtozkiaano.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtqddfppdm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gthutkaxgc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtyqdijget.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtfepzirmk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtegtnxsti.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtqrdpcmvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtaijdthfo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gtfjggidmi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtuadqjlwc.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gtxjrcevdu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtumlqfsnq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtuctzahmq.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtxfvdxypt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gttoueyyxg.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gtfcfilmgm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtcakamsgv.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtzfrltxbt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtsgzoerpg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtuzxkowxu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtrndwuusa.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtqzhtsmdf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtsvsfzvyt.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gtfblazbmj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gtsqbpestl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtfpqclufg.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtnrndwrzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtvxeckvmz.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtfjlzdppz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtjdbbnzsj.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsugtyti.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtfasysldm.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtnhiiyxme.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtpiiqunin.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gtzhsotltj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gtsqwzykhv.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gtpdoheatx.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtozxwehtc.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtrrygdwwr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtrcclwily.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gthhmyckje.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtawqnsjtg.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtpalcieui.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtvucpblzz.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtelesvves.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtxfdeipzp.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtswrmubjv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gtrpptosyb.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gtmgkgszdc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtfoiiziyc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtnjhifmmc.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtohsancvo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtspyrpgxy.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtadtdvukd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gttrpfspff.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtomdgmeej.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gteisrnegx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtbyiwiulu.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtyqrfapmw.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gthnxkqpjs.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtwchinuor.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtherarcdp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtpdaeitsn.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtjhdylbte.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtfmiyahmi.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gtyetybgvl.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gttltgrmuk.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gthijyngpq.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtxzptmqdo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtjopbomme.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gtmstukpxi.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gttxmdxpro.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gtvcyhszvf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtyypssigh.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtkitborfw.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthfnptqrp.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtyvlgzdwi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtjhgeozke.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtazvoobna.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gttqmtxmei.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtdecqqfqq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtbnwoqczz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtxmowlcmy.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtvicpidgd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gthxjjkmkj.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtznhiwalz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gthnctkrae.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gtuxcyxcjt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtzjiknrmt.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtxtktbgai.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtobfomzot.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gtwqeauyhw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gthfpysvgt.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtzdenxytf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gttsnbrvhr.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjuivcvoe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwxcyqpad.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtukqwhwcc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtjmxvgzxh.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtiwfiobpi.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtyitnkzow.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtbbvrntps.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtdmkwojst.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtvsrjipwv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtprcrtenf.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtmwxtemul.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gtjxdlkpwi.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtekahrkor.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtkbloaioi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtmxihdayn.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtmvtbelvl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtujvudjrw.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtvejpqdbb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtquhtlhzd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthkssmzfp.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtdupahkzq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdrrwoaex.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtwpsaenau.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtddzidjsr.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtnuomhjdc.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtentqkwjw.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtqxxtyilb.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnirukyx.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtmpdvkdum.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtdzjbpjmy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtganmjamn.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtgmazzduc.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtaotedpmf.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtvsfrbwdg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtmvtwszpv.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gtzshmgysj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gtytiqakmu.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gtxzisobqx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtsxtaknoe.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtfqlkkman.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtklwakbei.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gtouzkhild.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtkdoiyfji.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtesaonzbx.html


<!-- 参考信息 -->