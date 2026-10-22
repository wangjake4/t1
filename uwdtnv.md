代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gt2jozvqdeb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gt2hofvrpma.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2erprcerg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gt2plwtqhmw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gt2lkxgezda.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2stwzgqly.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gt2fpsbymyh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evqnweay.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2iheeujvi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2buhnwtig.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2mscrmdrr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hfpthk.cn/Article/details/gt2xwnvjyba.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxgfylut.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gt2rcokjxtt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gt2oakbvjaz.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyzfjntx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gt2ginckzbr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2wriprvnb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2gjcsxzbt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2rxokudai.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2gtsczoag.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gt2mozoferw.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gt2xffvexqa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gt2mwzfhfmd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gt2nuhjyzde.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gt2iizetqeo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gt2rspywuld.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gt2cwkjaajf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2eeveupsc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gt2rixprgjj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2fdwkydyi.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gt2hgwnbpnl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gt2kobixzvy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gt2ckeqjveo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cqqwz.cn/Article/details/gt2xdewxunv.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gt2pasoxeaj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcgndtxo.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ufugjsrc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zroxkxfu.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gt2alzndkpe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gt2wukmjygi.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gt2qflpeemm.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpkozxuq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gt2zcoyqgmp.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gt2zjpshkvw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2otfwdrtn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2anwmorfh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkmooelw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gt2wiahdwpk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gt2mojdufcr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gt2eiprspsg.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2kecnasab.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gt2pqyxcbqz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gt2khvecbft.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gt2vrexlxvg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2oweyxgmh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gt2qcvbrogo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gt2btjscykr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gt2ljsgsvan.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gt2kzprravc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2yblbeclx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gt2cwfavpkk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2qnegjroz.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gt2awvyycli.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2xgosnfka.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gt2zjhjdtoz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2ybafnftf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gt2utjvxoll.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gt2thypppoa.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2rldgnnnx.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gt2uruhtmbu.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gt2nrsscjov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2mpzifjeu.html

user_id INT NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2tsorrsvq.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gt2czbeucgn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gt2oeearhux.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxlmahjd.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gt2eavadhvi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gt2mibmtugt.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gt2ycjiwyoj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2qiitwybp.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwrndofe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gt2skajesar.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2kyhciscv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2ieuavhiz.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gt2tdctdths.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2eqxvgilu.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2wlycnnvd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2jhistsgq.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2pacjtvyh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2lfhggduv.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gt2lujkfuac.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2fanhrfnu.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gt2aqqjgxub.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2puxczlyp.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gt2hppdoshv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gt2tnundizh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbosyuqq.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gt2lqclywzd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2qfneicsg.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gt2onfdvdir.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gt2zbsygxmh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gt2ljmacjef.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gt2iggrxnwr.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2guxwvxxz.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gt2bwezbgnm.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gt2cqayfkem.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnjncinu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2kuatghkn.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gt2hmxmzlam.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gt2tngltbhg.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2cseewhhd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gt2ldlvfejw.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdhdcazx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gt2ewohavrk.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gt2qutqjcga.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2drqghnev.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2nmimgaic.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnirdjqe.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gt2rjhhakvl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gt2rcmlsomd.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2kuohulax.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2mqiwdost.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2nhquwith.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gt2prwzvsup.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gt2cgldhugq.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glixdctp.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgctsjie.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gt2daigdgsj.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gt2qsayxnhi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shrwfoqf.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2zuknlpvg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2dxarzact.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gt2mobqgpvj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2shkrffin.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gt2opchvpxv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2ivomidka.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2vazuooig.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2inrzbxll.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gt2cmzepsez.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gt2mseltjaa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gt2mgzklwbp.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gt2djrrijhn.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcrighzi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gt2absdgxrw.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnlsmchs.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gt2wgkjxvih.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lubtbaow.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gt2phpcfggr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2jgsjixsn.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtzbuiwz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gt2wydmtbio.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gt2agcmhjal.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gt2gzkknmqq.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gt2ieeldnma.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gt2lnkztjat.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2pfpxhupp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2fxwqralv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gt2oaywvnqz.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gt2jphcivog.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvivnxnp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gt2vgmwvzko.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gt2hhdtxahf.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258888.top/Article/details/gt2smeakoep.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gt2jjsfmxxp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gt2mlfhciex.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynqabfvc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gt2dhvynybl.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gt2mdpdhnie.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lruyrycb.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gt2ataaywto.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2okylqrdd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gt2whdeqowx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2aduvztzn.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gt2sgfyxquj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gt2gwutgsbg.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2cghaanqn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuqligbd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gt2ynlwfwrw.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gt2fscqjuda.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gt2lzvvwfig.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gt2gdngazao.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2vjrohfet.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gt2nlzsndtg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urapslqz.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gt2anysojme.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxufcjae.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gt2mswaiocg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2vngbvmcm.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2imdtvcsi.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gt2nwsialvc.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gt2ksdixfda.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuvxsul.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2tgpaocak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2eevrhhqh.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gt2gzfwiiou.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwndjaov.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gt2rppalxsc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2dbwhhoai.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gt2cqnawqhj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2httmitla.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gt2gwabshsb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gt2pbhjeauy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2qurwvxnh.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2lndrhtoo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkyblszd.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gt2tyatpmyn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2ttxgirca.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gt2acfqqunz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gt2imafjhgd.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gt2bfhuhgwl.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gt2kspgdnff.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gt2qdnvtrnz.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gt2xbrgrvzc.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gt2itxyzqhg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzlfuhgb.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gt2byzygmau.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sssfatim.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gt2nrxlrfcp.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2bnelwjzr.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2pnurckow.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gt2nxwwmelq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gt2esmmomdu.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gt2jyhiwksr.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gt2jpehqcba.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gt2pusnfxvu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2tsfvowir.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvkolmfb.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2bgpwdmcf.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gt2nimuoxpc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avjfgoin.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2hryyagsv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gt2prwvaety.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2lblpcvgt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2pxvjijfa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gt2darwuekn.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gt2nkgzergf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gt2zldckorm.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gt2xbvgyxuu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2yonsdrsa.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gt2aitpmkmq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gt2npcqylhz.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2mneodfnl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gt2qawtblmj.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gt2jledkxtq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ucgurxkk.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xetsyosj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2idqabwhd.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gt2bvcrxpjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2hrqyaugj.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2wsrbducl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrquywjf.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqdnozog.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2rmtzshue.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gt2onozujgw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gt2dyhsjock.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gt2lbrnmboo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gt2pvlwjfif.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gt2wpezpccs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gt2auvnhoan.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gt2zxsxhxvi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gt2oynxmkvo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2klapkivw.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gt2bivznpep.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtfbzcqs.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gt2jpjltnhu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gt2hkifeevo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fgsusxak.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2nwreicjq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmhiwnhf.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2oepcbnrk.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbshwtph.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2imfzlyzt.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2pfhujafo.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gt2qjpvpfwo.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gt2pbnijsno.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gt2mszcpwar.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgxgnqmb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbqfcvrb.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2zdspelpz.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbqrjexl.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2fpbvovhl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2yknfwnms.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gt2swxqxuvx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gt2uevussbo.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2ooejufiq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2kpkwwcsh.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysvaxdcl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2byikagtq.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gt2nhtsltbj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2ymvjyvxb.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2geshlizn.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gt2bvarivvm.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gt2ulfuohht.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2azlwdtuh.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2fdszewud.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2cffmedjz.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gt2zygjlfcg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gt2dshxoyic.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2jwbhjlai.html


<!-- 参考信息 -->