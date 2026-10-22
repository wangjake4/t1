代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2nqwazfsz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gt2jekabkgu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2vnjtlbwy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2chnatufs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gt2ylrmzgbo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gt2whtueqtl.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2mcirawlh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gt2rdrolhpn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gt2qzttdqgx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2ryyxcoll.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2qijiyicg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gt2dbpcuepd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpyhihdy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsrbskwt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2dprjemtl.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejfpeqpy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gt2tpkjibac.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybnzlfar.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2fvbxtppf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2tzhniogc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2revpnbbe.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gt2bvybxrir.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2afskuxoo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2ijlsvjjt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gt2nvvmkglo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gt2hbuiltse.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gt2lqdejozv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gt2xmxqxaci.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2hvgeqcih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gt2vluvsmtb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2ezriltlo.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gt2zwdhjmob.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gt2wybrdolh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gt2kxnxyyex.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2lhogbjix.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2buhwumkl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gt2aabbvnur.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vekfnqop.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2gmwjdsns.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gt2vsgizqtn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gt2ewsuafhm.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2eobzhrlg.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2shgwxnci.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gt2dnbtqzwv.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gt2dwospnhg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2yyfeklhj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2qkavhbzx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gt2dnpvpydy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gt2peqaauef.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klnxutbk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gt2xuvzjgbb.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gt2ckgnjmyi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gt2zamksnti.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2tyqxzrya.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gt2gehucfrr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2qtrwsayn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gt2nefuanou.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gt2upctfbqt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iozzuksk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gt2bezaprti.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgunutuc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gt2beuofxdd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2efvaswdp.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2maopacpa.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gt2nblqbtcp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2zygpiakq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2ioqxomhf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gt2urcklojg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gt2lziivtvb.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmvrqjon.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvevetqy.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gt2nmxlwujq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2qlbhzglc.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxzurqld.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2qxnuttep.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gt2yfszajdu.html

);
来源：http://dali.smart0.xyz/Article/details/gt2mxcekqmy.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gt2tgjwubov.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdlifjaw.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gt2dpaaatdw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnhvwxzd.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gt2qxnaodgl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gt2bgvrrqkn.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gt2xcyhpwcz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gt2owmcjcmh.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtlfxhvo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gt2azhpnyjq.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gt2fkoswbxv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2iwttkynn.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gt2vpjohrea.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2qhhycldz.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gt2ynqhklvk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2puwivwnu.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gt2vuetjoiu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2twgeqcuj.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gt2vunlbndc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gt2dkauhqyd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gt2yrgtqmgc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbtlhrm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2hknxcelj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gt2kfwgbaxk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2rpejwydg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrvbeshz.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gt2vpkynbuj.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2vnaavmbk.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2oeehhldd.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2polxnyrb.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gt2hzpnzbwl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2qyclrcgk.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2ejmenvwk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gt2ertygdna.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gt2wfskvsyf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gt2mprcxyyi.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2qhwnylmr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2flqioute.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gt2lniitetf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2hvsvvvzm.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gt2gvmwjuis.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gt2eawvjllg.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gt2naibgqqo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gt2ijcvfkrz.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gt2gaittgvt.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gt2cpdvwqkj.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gt2kpppcmwt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2xlqlxbue.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2ohuhwkov.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcxquvxi.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gt2lxwuutai.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2ybhgmovx.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gt2jtlgfqcd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2hkqacbnp.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gt2qnvatiaj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2kqwsjrtc.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnxteeki.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2gtobiiso.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2xuonxwoy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gt2cogqurfk.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2narbdknb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2hjmffaas.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2unfuwmmg.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gt2ygedbiun.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfprcxll.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gt2ztnlttxy.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gt2ruvulqur.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gt2pyaikubn.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2ggfyobtu.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gt2scfkwjdj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2gvhvrohd.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gt2zvewetzf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2bakwoxuk.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkyrgjwt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckzsxgnm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gt2hrqwcuhi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2blxrcocg.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgbrosjo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2hcfvdgdy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gt2plmujfdk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gt2zxncotgn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gt2osrczest.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gt2lrnjkumj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqzufhwb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkujjvfl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2kveikitt.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2emshelvr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2euullgpb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gt2acslnebh.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gt2espiboys.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlgyhqkn.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gt2rruvybxx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gt2ynalxopy.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gt2hdnezlsu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2snqgctuq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gt2mjqthcgg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gt2nugddohw.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gt2gjmchmrg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gt2sxcdcphh.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewwwxxev.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gt2exirfhwh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2vntlgrah.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2jqmsvgok.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2aulzwetz.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gt2duydsggn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2aesqsiov.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gt2ohwhzrho.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gt2bztaxxwh.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gt2gceeaqvj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2klxxcizi.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gt2uhluwmpt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vuzjtxct.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gt2zkauqabz.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gt2jeffpsqu.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2bzovswvu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2vueeorrf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gt2jwloyhly.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2ospkdaia.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2sioglxic.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdlkkmsj.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpwiocyh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2aopzdreu.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gt2cgkkaaym.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2umhdwypn.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gt2jaiprnfg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kktjwohy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyknyzlu.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gt2qmivcccu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jelgiodm.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gt2yctyqlhi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syvxoshq.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjgbzqhb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gt2radonqzg.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gt2zcojkxbg.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fofggvgg.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2gjiepdub.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2flfwwewf.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gt2dthiygvu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gt2zuyifibc.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gt2fwmdrmag.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gt2dmmgnuxm.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gt2sinsizfe.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2lvhoiinv.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2iydcxilk.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gt2xhkqjbsu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gt2qprtlqrn.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxsyuula.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gt2wymsisip.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2ieeoqvui.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gt2hkdldasr.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gt2ecjvvjvj.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ngwlidua.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gt2uykoccxl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2priasltd.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gt2dgxuovov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gt2kmugmbkv.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2chjdaylx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2ibbzwwoc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gt2dvmtevdd.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gt2dkrilwxe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2umoheqid.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gt2hugyaljm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gt2tcqglkzs.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gt2aniaroal.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gt2elmwiddv.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2xznwkcop.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gt2dnlvkmqw.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2usncgjfu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2shwqlgtr.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gt2iwuzjekq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gt2nfurejsj.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gt2npqtpaaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2kenscpmh.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2cuzalpxk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2djmwdght.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2geqpnjgs.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2caklrqqw.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2clhjvzkb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2ibzlmeha.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2xsbsxdig.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gt2uijnlghs.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gt2ppcsfkjw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gt2qdszxhnd.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gt2nkeobpau.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gt2hzxjdlri.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2ufklmwmr.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsbbpiyj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2mczxljms.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpkeimvf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2iitiwkau.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2bkgbebnl.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gt2wdeeeskf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2qpwwxswq.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gt2nbzprnny.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gt2bivqnrob.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gt2ujfvhgwf.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gt2oayghptr.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gt2bzvnvezj.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2mnzgyqos.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gt2zorontya.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gt2hlazgqrt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gt2cmwwsign.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2hgawxzed.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2ivapygzg.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkqaovub.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2nrvxluvj.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gt2dwykpfwb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2zqtvpayp.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gt2ayakybse.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2sydkfqhb.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2fjodsaop.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2aksedrgc.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gt2rhizglhe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlaeydxv.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2smhjnfah.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gt2xwhhgrvu.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2siktpxmp.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2eeplolpo.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gt2yivikqfe.html

esac
来源：http://dali.yj202588.top/Article/details/gt2ivoleiiv.html

[R12] for 遍历文件
来源：http://dali.zhixingplan.top/Article/details/gt2ldtufqal.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gt2iyeepwzu.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2yocfdbsk.html


<!-- 参考信息 -->