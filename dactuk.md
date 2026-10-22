代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2vswoklzz.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwqfkqoa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gt2vdjpolyl.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gt2szgowtqo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gt2alrceuks.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umfyegxr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gt2aoenrvve.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gt2knvjbiwo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2iydhbygt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiutghan.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gt2epyidfzc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gt2bimsvush.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gt2mudkntyf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2illbeslq.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gt2glfchqwx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gt2yzphrrgj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2kmoizrtc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gt2lmlvbqsr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2xgmxekta.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2yinfjohz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gt2uqqtxioh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gt2fsuzqtft.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gt2gfgnvgzc.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdtequol.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gt2bjgebwyl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2mxhsvjsu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2cfbwtmfb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2dfvkjica.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2zafsavbn.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvsyzgqy.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gt2qhdnyqif.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gt2ybfvachl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gt2tzxvdyxn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2bwjvgdzo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gt2dflncgoc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gt2phueczas.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2zpwhxiwv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gt2zxyokbxl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2iucykgom.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gt2pwmswijc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gt2zvwsxxbi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsxsyzyx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gt2xdvgovbb.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gt2cvkrehai.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gt2giwlhblh.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wtxgmset.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2ykpuamzs.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gt2huquafnr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhdrweq.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2rusyygjf.html

[P07] 防抖与节流
来源：http://dali.fzhhl.top/Article/details/gt2asciglro.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gt2bkkljwhp.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gt2kdtshgob.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2scvcqibr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2ruzjhheg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gt2aadxvhqr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gt2brfsnyqa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gt2iadgseia.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gt2cgrgwcov.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2eodmsgsu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gt2sssugmwv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gt2kbrqkivx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gt2axkkhqjx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2idetyldz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2njizbmyb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gt2fgezegoe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gt2rxdoimaf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gt2lunumzyz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gipbaymq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2qwjlcjsh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzsvczju.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2thmowpla.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2fzfytzov.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2cpthjeqz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2slelhuen.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gt2zmfjbpvf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cucudq.cn/Article/details/gt2bxitpscl.html

);
来源：http://dali.ivvv.top/Article/details/gt2yvvnkhgl.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gt2vulfkump.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2sjppaqep.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2nuwqyozn.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2mswlzqdd.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2qbidgokx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gt2zrddudht.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2okwimhhc.html

[Q03] 增加列
来源：http://dali.guowangkeji.top/Article/details/gt2tgxphaoe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gt2tqzkhqju.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gt2zzolkbhg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yvedp.cn/Article/details/gt2sgpwnnxd.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gt2baydcjvj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gt2atpuvbyn.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2vrgswbgh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gt2cykwfjrt.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gt2jlusbioq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvdzskfm.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gt2xfumzmte.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2jalnksnb.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gt2hphpzkrm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gt2egnytnhr.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gt2fbxlycuh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2aembjksp.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gt2lruomqyw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2aurrlwar.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gt2lncaenqh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gt2nioxylgy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2lhogsyrn.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gt2woghkuxy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2gzapbyjv.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gt2aucarvjo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gt2afquckue.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gt2fkwynoli.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gt2uvvtkvgs.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2aarlmpvm.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gt2ozlbanxh.html

SELECT id, name FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2sprrftxu.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2gmdaaopf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2uyuyajma.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gt2wcldovir.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gt2kytzwexe.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzlzkfwy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gt2ghxcyznq.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2icgenmpz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gt2gsixobyd.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gt2seevpdsc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gt2tnahoxuw.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmfaruro.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gt2rdlcggvz.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gt2vonggpic.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2ztlycqpw.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2bzjmbjhz.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2xyuzzblu.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gt2snnsscxz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gt2gkbzjrvh.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gt2nbswrhvt.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2arykrnhi.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gt2rpviljgg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2khktyzbu.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzeutbwp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2keqyazvp.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gt2ouivmvwm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2bwxvybqk.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gt2cpwvgtow.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fesewqkj.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gt2vepvenmg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gt2ybfoizuy.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2uthficea.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuzbkhrx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gt2linmnbst.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gt2skecfxqc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gt2yihhdcim.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gt2iufzmbgl.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gt2vjopdqao.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gt2svvoagsx.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gt2wzmhphop.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gt2pynorwal.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wiwxohkq.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gt2fyxhjpwu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2ohqqjvsl.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gt2yflmzwvx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gt2rkxsptgp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2jgjmlsfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfdsrolu.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gt2mixgyjru.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gt2zsixsuws.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gt2rylibpgb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gt2iqtsuyli.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2lrozothb.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gt2jtyjyqvq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gt2eikxoird.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gt2ntgvkzrl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gt2odogzvut.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2fdstxqna.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpmnjgtn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gt2vlqcokvg.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gt2mfeofsrw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gt2uajmrset.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2rzdttyjs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2irsyyfdr.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gt2tijvjwwa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2inamhxsa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gt2nujhqihd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2ftbtujtw.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2drnikwgi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gt2echfsunl.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gt2atoeiveb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gt2sidsnnxs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gt2hskwyvio.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gt2lyzqxepd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2oiaeuxih.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnpqjiqd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gt2vlfwruio.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gt2yszqberd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2lckfjrqt.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdmswvqy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2jlfcmhie.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gt2ededlysl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2pqnqskxt.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gt2dqbzjhjm.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2pnjrjxpu.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2eqmtjmux.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2fhnewvst.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2lbytwztd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2cqrpxnmx.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgqkumqa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2oavsvjwn.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gt2ohgmhftv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2lbdqgjbl.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2sswokysh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2uclfbpvs.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2hpvmfeth.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gt2qxliovzi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2cbvuvjdt.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gt2lgmogdza.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2nsismwbp.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2tsbtknom.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2gyhhrpkl.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsbsvoqe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gt2fjobvhec.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gt2brbojcoj.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2kazacvgb.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gt2hevvgzrd.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2xjdydmvw.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2eorqcfkt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gt2hqmraiva.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2vfbyujqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwaufia.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2krmieixa.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2aotrxbvx.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2pjfjpntr.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfroqxvy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eragkbqm.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gt2emoivctk.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psxfsggw.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xirqwwqg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gt2nootveqx.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gt2wtnonesg.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ktghbkwl.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gt2rtalgcym.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2chtfhegt.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gt2omlrbgix.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxukbgjc.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2aznzvbig.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2lochpnpr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gt2wbcbblxt.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gt2prvqehkb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2hykuynfj.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gt2gegdpowd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gt2ebckuelr.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gt2mrjpspqi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gt2sixoeqxj.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2bcakygum.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gt2boxucuul.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2oosbdarc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2qmifnfnf.html

[Q81] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gt2ekbpvnsk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2btqvnfmh.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gt2azevaxdv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2vdkyznur.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gt2kkkspjgs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2bmhwojwe.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gt2xadbrldh.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzxyzkhr.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gt2pddtvumb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gt2dqzzizyf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jufeeree.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gt2kkudcsoc.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gt2jregompp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2kxklmafg.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2qdelhibc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgiwdsia.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2tvjnsazn.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gt2wwfcmzfi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gt2pxuqzejo.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gt2gavokvvs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gt2fcdrifyr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ubmiityq.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gt2lgocwzfp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzkyesom.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gt2xpeseulg.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gt2ngkolrzq.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2edhhtrpg.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gt2pcnpefqo.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gt2mezneipj.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gt2phgmyvwp.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gt2lzkodekp.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2gujpzbnv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gt2vvskoewq.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gt2ukblpblk.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2mgypqhnq.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gt2rrmogujf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2cpqtbqsz.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcmxoezl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2wjaebisl.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2mwahvkpj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gt2daqwydih.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2sgqxdbdp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gt2zhmpvynk.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2mhwsokql.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2ubiawldt.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkjpexnn.html


<!-- 参考信息 -->