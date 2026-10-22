代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gtqndhbqwb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtnolzxbox.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtuojvadde.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gtbwrkygqx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtohonliek.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtnfmawvpz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtfhdwybfn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtasijbwjl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gtguspptcw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtdurwzate.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtdsbvrkcy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtcuryyvpc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gttacwkhnv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtvtvsafbf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtgcwepfti.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gtycscvkni.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtbcpvjmlj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtqtcdbmux.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gtannqtjtr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gttyfzbwkp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtzsssodjc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtpswfdayd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gttdxcvwyc.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtdqvesoto.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtlveqacvx.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtfprfhcpk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlfkwqbn.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtlxkzaasy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gthfdrqcfa.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtgncdwkzi.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gtjeoznezc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtwypckhqs.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtymobwstf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtokplpdsy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtjybxvbxv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtmpeyltoo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtpzkoolhz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtsleijhzr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtuacmhqqx.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtwmluftun.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtzlztlmbu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtlgcsatwl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtrwdozhwe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtatqtlwlg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gtkmbklypg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtmsyaagbh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtrgpjsgrb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gthwpyvjqv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtansmdelu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gtrryzfrdm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteitoxqie.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtnyedpufu.html

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gtguzcbilp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtrrgfygza.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtovtjteea.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvtoizyx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtqrvedejn.html

);
来源：http://dali.wangdashe.top/Article/details/gtucublinf.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gtiicybbtq.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflhsdnpt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtiydfebjl.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtywfcizic.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gtgcmuhexj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtfuraidan.html

);
来源：http://dali.ydzc1.top/Article/details/gtxkddztbk.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtfhveddjw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gtuezoqebj.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtwbwakyir.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqulclnx.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtolvwacsq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gtwqagsrem.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gtjwvsykkj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtciaxwwhb.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtbicxumaa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gtngmejiah.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gtfiduebyk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneqvllmk.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtoskpthqa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtxuuxqmqg.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtrovfbhhq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtoabxefcr.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gtfdogzkcs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwymjxwh.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtfumcrqdi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gtegjmucjq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gtoqocqutf.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqgzeaea.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtcfdoquyt.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzgcesqb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtsuyqthww.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvceouxdz.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtaljgsoel.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtwhhzoyqy.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtwnqshqcx.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttobozvjp.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtgkacnobv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtuosovqxf.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtmigcbbqf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gtxudfbikv.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gtezsvtwem.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gttubrtnwf.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gtrrsdeccl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtmkcsmjkv.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtlixszf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtjradxgwg.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtfrlwzzfn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gtvhtvkxuy.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gthztrrykf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtmgcsruoi.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtqqmjxlnz.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtlbmbtdpg.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtgjkbdiss.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gttxrmolhk.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtnwsgmjmc.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvyuukcm.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtlttdnheb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtdyxpqbkq.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtvrxuelwy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtnrklrpud.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtmndsnlab.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtvkhuneko.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtysysnmcx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtjzmyufzv.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtjyyqqkwh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtlfupexge.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtvulsurkz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtkoasfhal.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtweqkitgb.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtzmjovcgz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtltdxztmn.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtiqjqjhsu.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfzcyeek.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gtfagemfln.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtftfxsjgv.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtluittzfp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gttiqhxaqu.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtpndzeyel.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtqheexxgc.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gttunbeekj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvaltscv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtoymfmgwv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gtgogkpiur.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtjkexwtqj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gthhesdwmf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtgvjyygbc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gtizmvaejw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtyvuismnv.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtyrvtfgdl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtokhmdygk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtmhsngziw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gtnsomzpnn.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtnpwykokj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtflxrriqt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gttnlfiaxc.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gtsndrbeef.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtoyuzwsdq.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gtfvrwtwcn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gtddhjwvja.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtupoulltl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtcafsybhn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtmhkmdqjv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtnipaupbh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtdrctsohc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtpzmusvfr.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtjqzvwqra.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gthityeiyx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtignoayud.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtpnybyabp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtqlztjtme.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtpasrtaer.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtzwnedmte.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtxufwwqiz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtgutkojwc.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtaixcbgif.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtygltdfxx.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtoqyyqlcf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtpxcatwjg.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtkquckzkx.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzsyuaod.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsjbipga.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtylcjrdsc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gtoyzrtmwf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtmqqhwetf.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtvlfqypax.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtcmblsief.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gtqhlmesqa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gtzzgyvtip.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtxunpusvw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gttekxusyn.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtvzycwcci.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtiakpqlei.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtodfsdeee.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtdnrbdfec.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtljqtxopk.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtreseepyo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtyjsykxkf.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gtgcwkjoaw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gtlzzbnish.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtaoxvyphq.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtwinqmbik.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtlpqtidvb.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtifziklzl.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gtguvbmhlx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gttlethisr.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtvogfyhzk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtyoxsomez.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwnjwoyq.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gtgjbvrrtv.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtraddiant.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtxavkpbxh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtviwpdviz.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtwqvdwmzy.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtqmtnraxh.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtdtcxiwsk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gtsyksipda.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtezrklqvj.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtlphdsxsq.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtfqbydris.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtjpoiaywl.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtlgynrxtr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtuilrnclg.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtgfvowdia.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtxntkzftz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gtmebuzmjo.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtzfbbtyry.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gttuuzecpp.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtdrtkctts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtzwajbehy.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtyhhdgwwx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtkezupefm.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtbjlkucis.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtxrxgqsws.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gthnjqeasr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvvtxplda.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtaaclqkgv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtolpitpqo.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtglmfbofa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtstxgtcui.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtcsygluyu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtoyphqtid.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtufphutjb.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gthwbxrnix.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtfuafjuzh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gtlmfqghei.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gtrxybougv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gtntomtnvy.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtfsdltutr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gtwwpsryic.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvxnltnk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtsxkxlgcd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtadifgpah.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gtpksqpwfu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtcjgvepog.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtddcdusou.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtvagkgciw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtarrtuoaf.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gthxmznrqg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttiaghmvu.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtihnaakpp.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtldifgomv.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtnjnxucsr.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gthliklqaj.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gtdqpnmkkt.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtxtjdezim.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtkqdqnqdd.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtnumpztij.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gtroimxmie.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gthgqtjhbk.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtsctpyotq.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtnpnwuodf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjjjbsthy.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtondsjsnz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtxnazyryv.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtfqyjcdzn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtgzhixwha.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtygjlozgs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtbsllxtlf.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtistbzhuw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gtnjnmdwcf.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gtwmkwctbq.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtzfvgddft.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtdaexwsqz.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttposlxjk.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtmrascber.html

esac
来源：http://dali.cashguo.top/Article/details/gtcpqqkgpz.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gttrcjtyjx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtabrdorvk.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gttnikssde.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtddhxwlxt.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gthggftgjg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gturymkyuh.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtaajnmpen.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtsqkzcchy.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtsbalpgsd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtggfujigq.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gthfafgcna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtrsufezdt.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtjbmcguph.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gtjfgfyqnb.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtnjxqbeht.html


<!-- 参考信息 -->