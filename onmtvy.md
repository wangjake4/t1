代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aibaodan.cn/Article/details/gt2torvbicv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eandvqbd.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2fowmmzor.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gt2ihatysgy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gt2vuxmkmlf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2lvlekjkj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2icgtlojm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gt2abafypmg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycfllpei.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gt2hogzetky.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mztyykan.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gt2zpmqixbl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gt2ghzzrhxg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2vaxzdotl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gt2ujjdbklc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2tpsfmfog.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2cnstdvey.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gt2cqjovtvn.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2eqlwzihh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2xpzvbuvd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwwpryip.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gt2wcygoixd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gt2srlhhnip.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gt2ukszuhtd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2yxskoyxt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2oykhhcbt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2pogggckm.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gt2buytkapu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gt2llikcybx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gt2ulrluanc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gt2qzlfziqn.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gt2dddwaged.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gt2gtmkqzhy.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2cspluipg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gt2murzgrln.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gt2yloosurw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gt2oxwxmqfn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htiscimh.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gt2yvpcvmpj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gt2ddsutswx.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2bilelqgn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2dkqqxzam.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gt2waqojsba.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zetvtlbr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gt2dkobbccj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gt2qvqhmwrj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gt2elewjiqr.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gt2sdxqvbjd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gt2kcrfftmo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoovtccp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gt2nyrpzjgy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2qoidhbjd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gt2ghspgdzh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2hvzhkwin.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gt2znbbzwlz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gt2zfhoryjn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hdfkrjfv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gt2exhbudzu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2xcygvopc.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gt2qoynjsgp.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gt2gfxxjtfi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2hpbroewr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2aqdvdwqs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iihqnhgo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gt2oylulcfn.html

);
来源：http://dali.redwolf501.top/Article/details/gt2kfsgrqps.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2yrfqblva.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gt2wzzthohq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2avgamebf.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gt2ammgzvzp.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gt2ettsnpti.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghblcmvh.html

);
来源：http://dali.guannengcc.top/Article/details/gt2brumrfkd.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gt2fydsrhdu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gt2pznrdfji.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gt2itthduyw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2slsnjokb.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrlkeyil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gt2yzfbmari.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlmfaswy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgbeqkjl.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gt2metqlhwv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2ghtwrrfh.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gt2arljquib.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gt2mzvhbrgt.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfsneahh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2bgfrxljf.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2yynyfeis.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2qhhprehc.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2ujtpvuqc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2sikffbgz.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gt2jymoqsuc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gt2keqkyqtt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gt2tyhcbywb.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gt2xkjqgfeq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2cunnrilc.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxdxdiyk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuitwlth.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avixjkqa.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2szeseufy.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2tcqnmutu.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gt2njckolrb.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2qjyjsudl.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gt2hqnywved.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gt2mkjkuwfc.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2nztugslp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gt2efxxdseh.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gt2yktmlxkh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gt2sepsstsq.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odvhgxfm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2sjamqvtg.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2giyxaspg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2xqhnjqqz.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gt2dhkoscbz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gt2qaqidecw.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2faxorfci.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gt2khmzqbef.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gt2mtkpdnbk.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqpnatoh.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aytvrtlq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gt2pxrormtp.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2eswwblbh.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2woldmoiq.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gt2mfcahsmi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2lrbratlc.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gt2ucwnhuce.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2zranuajd.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2uhdbvgnt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2fmsnqrbt.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gt2rltxtscp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2jbsajktz.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gt2bjzuvnpv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2otoqblnc.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyaztknw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2ghgwydqi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gt2youiiude.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gt2eatubqpj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2dyrwtvwc.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gt2ifopvftp.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gt2idszjljo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gt2oyytycak.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2vlquomzq.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gt2votjnpoa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2mqfsohga.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gt2dwseojka.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2uaxybiuc.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gt2fbfyrtmw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gt2lbufmdco.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gt2thpxwygh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbmthhsg.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlcmdwbs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gt2veiytgbt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gt2yfygowyc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gt2krotirwm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjyzyemz.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2omdtagij.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gt2jzhhwwfd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gt2tmwrldum.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gt2rtiotmlo.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2exqyxlyy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnnpozwb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2xxjvgidc.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gt2xrbexyqi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gt2avtsrhzk.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gt2faphgheo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2ynkmwmiq.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gt2kaowtbvo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2cjnfdkby.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gt2mgxqoklh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndxfsfkt.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywzkgzag.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gt2yyomvxmt.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gt2ooowoude.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gt2oszjbjic.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gt2plfgyvuz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2buphyyxd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2hnnrvjfg.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gt2uhtylbvk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vktrnvum.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gt2luqubzur.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gt2acnkntdd.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gt2eetawjdt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhfbofzh.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gt2qlcacvny.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2cdxvweay.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gt2phazvkyb.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gt2uwdqumye.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gt2kblgvccz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2zoibebua.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvcpynhc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2dpdiakne.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2lbpwhybr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2jpuotnbb.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gt2cnwgvxeo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2kvxnurlw.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrwrmyiz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2xgkgafnv.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyyuyznb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gt2ttaflnkn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2ilvrklpe.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gt2ifgsqeck.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2hypohnkt.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gt2rhxjnewc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2lqeipbid.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gt2ftjawqrg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2mzrwukqq.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gt2nkrcfiyq.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gt2zkloogtw.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gt2mcjgemli.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2erihnbqd.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyicnsas.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gt2uyatcwxo.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gt2uazdavrp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gt2fttmosfs.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ansfertd.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2nvtlhkoj.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2okijukrg.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2svrdjwyq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gt2lraysccc.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gt2nvrozqbv.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2shudtitu.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gt2xjgjegcp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxxkexuk.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2bqyplpad.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2jljlnwrc.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixkthing.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gt2zccmrxdm.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gt2mkxiguuf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gt2huomocnf.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2esqjpbry.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kllzusiv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gt2hlljrjvc.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gt2onrkclnt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2clhpkgyj.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmdxowwe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gt2gqtjibkp.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2ttdtetnw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsklruxv.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gt2yodoovff.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gt2sazbchkw.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gt2qtphggpk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2vtaergxj.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2yzacnimm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ehkvsjkq.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2jtbmdfzb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2gqbcpdoi.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2nstglvdo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2vcrlykiv.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gt2zhvoalxg.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2fdgetkgg.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gt2kdvcpzla.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2omwjppff.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gt2picpkifk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gt2zdaufrqq.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2wssjfena.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gt2ifidhtnn.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2njqitupz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gt2shbdctif.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2bytsfjma.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2heyvxikl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2mkekjwzm.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2ifgspjzf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abuunjvi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wzmuzqbe.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2iisvomkv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hiomtext.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gt2wjvjkqac.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gt2tcrcfdou.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gt2dtvyfphy.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2gmlzrqoq.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvnzmrcv.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gt2vrqnxsoz.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gt2yuscliin.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2gessvoew.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gt2vjnvbaly.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gt2jglglmwq.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gt2lqzradnf.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2opzmnvrm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihxtasak.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gt2stmjaqim.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2ijwxeytp.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2wwsntzja.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2qggfvqdq.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgodtwlg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gt2gnfkhrlo.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gt2hgjxddfl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2sdrrtwgp.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gt2jzjguhlp.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gt2rojslyar.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2twfojmww.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2gpzmolmp.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gt2ovfjrdca.html

esac
来源：http://dali.aizwys.cn/Article/details/gt2ylecqual.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gt2pdcueeyn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gt2nqxsooyl.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwstgyzf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2djbirndm.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gt2ozhsolla.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2ruwmqhov.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2gqjmvzoj.html


<!-- 参考信息 -->