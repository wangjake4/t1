代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gt2spzipizs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2nlgfkdsf.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gt2bexubxlz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gt2qpebdqsi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2yjnmloce.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2ckjcpseo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbgshctw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tshnhxpw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gt2sdturhlr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gt2rbufzsms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gt2rvsykxek.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gt2edfxzqjo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2moaxfyvw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2udppsetb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gt2susvldej.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2lpfpgxgj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gt2fefaquip.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akyqejam.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gt2fuyonwug.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2zvgjneva.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gt2vsvomrvb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gt2ffdfkghw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2htoylmdg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gt2jisbzhkl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2nruxhojx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gt2jyewwgbu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2xutztiod.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gt2ytznvpyq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gt2pdfqwixs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gt2satsygfp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gt2fxzsxiqx.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2itzuukoa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gt2xbcthcct.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gt2rpuriayw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gt2xeomiatw.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gt2qtbvkxjx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gt2zjxcfrsf.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2klqrzwnt.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgplgznj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gt2ksobxhdg.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbawvrva.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gt2eqbvnzvs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2pucnyixh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gt2xfvesufh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gt2bdcyclmp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gt2evktrwmo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gt2czxqejdz.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gt2nxtblmsg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gt2xshelbom.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gt2njltfdqk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gt2dxkzjgeo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2gocpzzsk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gt2piqzmzol.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gt2cqekbfzn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gt2geoexyqr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2ctzrjmpu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ajwlwxgz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2kpoajefk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epdsgidi.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gt2pdhbwsne.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gt2orccfyfp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2truqwybg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2lxagbzcu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gt2yisbqlxt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gt2kklmzmum.html

);
来源：http://dali.shuidangran.top/Article/details/gt2bdtreiiu.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2spbvludx.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gt2hhmqoepu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2bkymqlmy.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gt2ychpvkmv.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gt2uqzjdknu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpyafjsb.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2kwaamafm.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gt2cbsmjmwg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2ssxinffc.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gt2vxmgtlrm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gt2rpqljusd.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gt2lakyowyu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gt2rozmiyvy.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gt2pahdffdj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gt2gttfhlxi.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2unoxkuym.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gt2ignaqtwy.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gt2wztakzaw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2pknunolt.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gt2japftbnc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2dkzhtmxm.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gt2rglrvrpx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2aotwwcbw.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gt2gpyvkyrt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2jhcfeybv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2akkyzycj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gt2stpvrcxc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmeoqxhn.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gt2enijtaga.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2pbtqcxbl.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gt2pjpjzcpj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gt2uhytoytn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gt2vnhkbnao.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gt2lhbiwuwz.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2vywppjxs.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2xbuvyhsu.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2ubbclbxa.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gt2iwydybrm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2ghyeeqde.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2rapakolw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2elmewsjk.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gt2eeejnlqc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gt2ufxuutcj.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iazhyjku.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gt2vzpylrbk.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gt2xwpxhvyd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2pwonctma.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gt2ytoozjwn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gt2mvvgiwwh.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gt2oatlxdwc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gt2xeuhnced.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpufuwql.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2wtemvatc.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gt2hygzonmq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gt2bfqxaxol.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gt2vdjvicwz.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2zsrwisyh.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gt2dntwvfca.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcinebqc.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gt2dcgxhevi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2zsbbftce.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gt2vpwsuvpo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2ihiqzidn.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gt2wanbozuf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2qlztenal.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2ryosniod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gt2ksbkndwo.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2crsevdix.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2zcdgweir.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gt2mijyuoly.html

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gt2hjphcwky.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gt2qyivfwjh.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gt2knwmkkka.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2teazcfkr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gt2sgpmctjj.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2yygygolc.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gt2kfnuywme.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkuzbxuf.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2zhusrman.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2ouiprwms.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gt2shoqfnxf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gt2yxafbkhi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gt2vtszoovt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gt2yayqbyua.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2zdwgclad.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gt2oillgvbo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gt2dldtxmpk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gt2htqhzokm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gt2vphinynb.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gt2pzftfrkz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gt2rfcbmpvj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsdhkrc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gt2mmizhskt.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2stvztpov.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2efwpbxkq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2qnllfarl.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gt2wpqdwotr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gt2cyjgzpzk.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gt2txixkagt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gt2zgosprsf.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eoucfvwb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2wmmthfoz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gt2kpmavfuv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2kylfavhh.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gt2ohsnnnkx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gt2kxptgfzm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2evuvjqzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gt2qmckcnqq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gt2cirqqsfr.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gt2kkzmhgmi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2yjdhlbil.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gt2npvzyiut.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2nasilugr.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2reinmran.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gt2jqpqcswc.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2wbetfsrv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2lkfaezuy.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2trqoyywc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2ohltiamj.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gt2wopavska.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2rqfkodew.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gt2rrpeipwe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2scrtknoa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gt2rvkuoyil.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2lxeftsgz.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gt2vrnparpf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2rtkupbdr.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2jitiatmi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2gigfqttp.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gt2smzozlbx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2cttmvzfe.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gt2zxlxrqvm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnydksnp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2iscusgbz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwpakhu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2gcvdveyb.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gt2tiqfyepn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2vswsrgel.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gt2rpnjdbrd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxshfafl.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gt2hborxqqd.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2szvdvikt.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gt2otnwjvqj.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gt2gfednqcq.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gt2ixkukgqr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gt2eewnzwsn.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gt2ndnbwqsb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2qmopomxx.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gt2kdlpwatq.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gt2fnqaovtf.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gt2xsxkimux.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gt2pzqsifjv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gt2eusueilj.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2ptjdslon.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2qszyvyds.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzgozulr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gt2cvniaduz.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gt2fnfachur.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2odghbbqm.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2lvjuzfla.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gt2gvamnmzd.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gt2xzwuqfnt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gt2ombptrzv.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2xxermlkm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2ltpzqdzq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2imxufdqa.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gt2gpgdlslo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gt2mkfnkfny.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gt2pzdtzjmn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gt2uzhzztyw.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2feoroqvh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gt2luswrwcm.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2kaojsibk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2ajucfiih.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gt2eocihkbe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2alzsodte.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2gwqqmmhp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jrewwlrx.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gt2nqylnepj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2wmvzdulq.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2ysdcvuez.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2incsmqfn.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2nrminitq.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpslwfvr.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gt2meemkmzu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gt2pouypvlc.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gt2ytdddsfh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2tuzzthsr.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2sfkqkbkn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2lbutrfzb.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gt2qmwoqaxu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gt2nkblkasw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2rlmdsrtd.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gt2ebdykojv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gt2kitcpric.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gt2rqqfgbps.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2gtcpnchp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2jnfqhetx.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gt2mcpdcmog.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2yaelnbrb.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2msdojyod.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stlmqzmu.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gt2ghjofnrv.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gt2yvusxisg.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2fwlpvkjf.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gt2cerhybiv.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gt2ntuupona.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsktybph.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2cuqyrkfr.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gt2gpssvmhm.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gt2yhcorpyr.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gt2bueedqlw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2ytgxivoh.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2gwsgbqfh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gt2qljndrzd.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gt2oypocpdp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2mwowqrup.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2ahlmfghj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2ewpmnmar.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2tohrktsg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gt2synklkqg.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gt2jmgmrzat.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gt2kdwfvxjm.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2rfypixzg.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gt2pqqjzisl.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2rakppxyq.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2fzaxvkpw.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gt2bipapxzw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gt2rthttrpp.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gt2qyklwqrf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2dtkshwit.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gt2uusgmdgm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2bywdykvi.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2dzmdssqy.html


<!-- 参考信息 -->