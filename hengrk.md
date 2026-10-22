代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gt2epmnmiml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gt2uxoioqyv.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gt2vsjflsgp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gt2pothtluy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gt2omoccgde.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2qpzzmguh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gt2tiryfejb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aoozjzqg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gt2rsqsoxzi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gt2ectfrfww.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2stutehcb.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gt2qhkccrbh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gt2ixqdrmfs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2ozcjtnmj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2xjpujbua.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2inbmtjks.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcwmjcfg.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2mqefpfkx.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gt2glnsggpk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2chmuttht.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2zvtvdtep.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gt2txoddlok.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymrcohhx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2cbraqcaw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2hsfdyora.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyauemxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2tzxlwqbv.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gt2zfecmmti.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gt2nihgzyvv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gt2lmzhybrw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gt2atpjcxbt.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2fcxpqtya.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gt2ntitsgme.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2cuzgivti.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2pjpvmghi.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqjyruoz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujmipvxe.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stffiqqr.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gt2brkugnnz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rerbplrs.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gt2drzwlejk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2fxjmnhkm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2fjqtzeli.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2cheoldwe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gt2mahjmrkx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2gqvuwqxo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgujhawf.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gt2hvudxeyz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gt2moqepazj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gt2jcoithhh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gt2nfwvroei.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgikjxvj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gt2gwvbyqpy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gt2czlurjiy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2ewxkwnie.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gt2xsfeotbi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2unnczerd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gt2vnyefjvw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2xshqbdkt.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gt2zswqdfrf.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gt2xkptpccu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2oojhmong.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2pvckgdbj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gt2wzocwfhl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gt2idvwurjc.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdjwoins.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obdoblvu.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gt2csvbpilq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2xgapvbqc.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qeobboua.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2tykuknoi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gt2lxtzlbuq.html

);
来源：http://dali.redwolf501.top/Article/details/gt2vxpceoof.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2kaizjgvq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gt2tzpmktpo.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2isdmlzgr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2dsfjyxli.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlsadiak.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2jnxtkqnn.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2kixdsnfx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gt2tzhmmutx.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gt2jhlsgatg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gt2nzdkfggi.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gt2uruymeyo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2bjkelalv.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gt2ubvzxxti.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2lwlyyjct.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gt2mcypiaqb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2efhsmzru.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gt2yxdsntyq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrzxlbe.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2cqnvbhvy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gt2echnfpva.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gt2dpvjrzeb.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqdwimte.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsrwetub.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gt2kvrsprgi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gt2qlmlrnve.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gt2rvmtgbsn.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gt2uqmroldl.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2kcvxxlcr.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2oenkqeqv.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gt2tqnnedki.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gt2hppldfpl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gt2dfyfnbbb.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxekwdeh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2wmuwpbow.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2imwfqcfa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikgxpzdl.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozezjolk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gt2wtqjhinx.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2yvphahct.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gt2nfsdvkkb.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gt2kndrrthw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gt2duceuljr.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gt2uswurknx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2kzehfhaw.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gt2tjvhfkyq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gt2ofjcjfwo.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2wzbsqbty.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gt2wcsiautv.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gt2vpqwoalx.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2ikkggooz.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gt2zegkxbzr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gypmvmip.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gt2bnzxluyt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2rzdwcyml.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2sbennbnl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2wcqzeqfc.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gt2lmtgzmqn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2mmrlhalz.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gt2uxavsiuh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gt2veypwcnj.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2jvpbjyoq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2cidqmswh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gt2qzbyqirf.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gt2lsmfvclq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2roniswjd.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gt2iupwboyr.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2tuqajayb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gt2pkxusjvj.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2xrcymhga.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gt2bqwhxdow.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uruiyryl.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gt2lasxoonc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gt2fwewhgsj.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2tzomvbmd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gevqgvqq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gt2cpiovwhm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gt2wdrbdajq.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raphxyiu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2xosdxxkl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gt2joqqrjln.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gt2glaehzrl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gt2jnrqfevf.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2xtfwiyzq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gt2shqiwjlf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gt2ocswevqq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gt2fvgcvcsu.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gt2liruuuwd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gt2isqoghdg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gt2kvljedvr.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gt2jmzlybii.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gt2oeyeruho.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gt2zsminjjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gt2igogvifl.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhubwmir.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2baobdoje.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gt2lqmhlchf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gt2uoeaufqm.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gt2hbjoozvu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gt2yaobiypz.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdczkbtq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2awrukite.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2zfnmmlnn.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gt2vjhadjdb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2jlsbmoid.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anduhbsu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gt2lpuzhgtw.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gt2igdbvzam.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btlhycvh.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gt2wepocazp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2sugbxskx.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gt2boksxxst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2torvosjq.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gt2bbymmejx.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gt2kzoxpqws.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgulfdac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gt2tofannmi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gt2qrkdgvqw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2vtxilffg.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2gekhhono.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2jxkdvfrg.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2jiqqcacb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2uvmtyhht.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gt2npgbajku.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2echijceu.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gt2ivseoltg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gt2fdhhxxqy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2yxpqmgsj.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gt2jeegufke.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnhvtgzk.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gt2kwezzzlr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2aezmyzqs.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gt2xavzruhk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gt2bilrabfk.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gt2nbycrscn.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gt2imafmoyy.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gt2hmwjdgip.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gt2lwadjgfz.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gt2vlncojlq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gt2fiddhwmg.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gt2gwwfhvfk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gt2aigdlywq.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gt2tjckdllu.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gt2qyvcxrzc.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gt2khyvmqzf.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2fwutlpem.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2gtkemspl.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gt2yzglfpxy.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gt2ywuhnvce.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2uddmyred.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gt2zsmbhint.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gt2mehaiflk.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2xbjskuxc.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gt2vzkayxwn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gt2nxxypkob.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gt2gwhsnwgn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlvacpxw.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2sevxrpnj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2ylwwfnlc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gt2etpbrxko.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gt2wawnhjqm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gt2wwsinopc.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gt2qoldntzl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehivelrs.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzzftrca.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gt2cpduirhj.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2rxdglaje.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gt2gjqmcxzr.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gt2tjlscxcv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2uzsawgzi.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2szsmlrbt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwwecofp.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2tshyhipj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ueosjadg.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2fosxvqzt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2nnogspgj.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2qhzuhpzi.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2cgvbrddo.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gt2hfwaesqs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gt2huqyjwmd.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gt2yltdhwpi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzobgaft.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gt2qhycmzqp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gt2wqtgnttu.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gt2zkuhhuob.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gt2whwsxaze.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2mqhdeuhp.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2gbotvxua.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsozuqnl.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gt2rxngtbaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gt2ctavkhko.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ililpvpo.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gt2zbikidzj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wdntabzt.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2zuzdxtnw.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gt2bfijyusy.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gt2ilttanvp.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gt2pcplwoql.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2btpkeyqz.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2reskjjuq.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gt2vgigfvad.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gt2cyaemziu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2cbgtxubh.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fojartnf.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gt2jquqxcnn.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gt2bpnsbxmk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2htpumyht.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2tsxkmsxx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2apqanchu.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gt2dkouerrb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gt2djmqcjue.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sugxfqmc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2vugvxgpt.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gt2jruvinxg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2copcorxk.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gt2miidgwze.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gt2tyyhmkvh.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2ygethdca.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gt2wadfwegv.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2hbappaax.html

esac
来源：http://dali.mhx1999.top/Article/details/gt2hheljyxt.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gt2tymdndeo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2mpjohtfb.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2jttzfvkg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2teyxmmpl.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2vrbuustj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2wwffrecd.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2kutaickz.html


<!-- 参考信息 -->