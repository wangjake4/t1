代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gt2hjmxuhll.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gt2vvbvsrgd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gt2ijctewum.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gt2pahwyzzs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gt2vrgaefvc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gt2ynyyyiyp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gt2lorkfbly.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2syqnsgru.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gt2yjzwyfvj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gt2bcbiynou.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gt2raqtidpe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gt2zhfpyboh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gt2haucjbtz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2iuguoimz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rolingkd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gt2objzrbmi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2wgvspyet.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gt2llfuctkr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gt2ruuznysn.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gt2xiahoiwp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gt2lyzmvmtn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idtmghxj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2znatnumy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2veyejacr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2iyhdqflv.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gt2mhjlzpmr.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gt2xwbuigbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2dvjgxzpm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gt2lejwaaix.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gt2zzfwemqy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gt2gjmnwutx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gt2xinhvmst.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eszkzhaq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyhiypsv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2psqlfsny.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gt2tfbcbvaf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjzypfds.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gt2pmytkfbu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gt2ekuxvfnh.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2eurituyd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gt2cpjumrcd.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rmcuehht.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2czjtdawl.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gt2nedvmrtm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gt2urxzvxya.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2ykacwbbi.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2clnjuqns.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gt2eagkabis.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gt2qmypajpc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2eauvizot.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2ignqimqe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2dddccxtp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gt2ikmqcrhp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gt2qsfahaks.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvsgntek.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gt2zrvvipdc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pexxxeqz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2okhcxmnn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gt2ccjayabj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2dmpysooo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gt2xbemrdpt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gt2faqtxmif.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykkcbhfx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gt2mtbpyblw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ixelcpyu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gt2owwjhcbk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2zbqegzbg.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2gflipfct.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2iwddrzmw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2vvpttjse.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gt2nxvsdina.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2oyxragti.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gt2krybquac.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2omqiwfqh.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykkcdvnc.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gt2zgevntzc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2aslejpdn.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2uzantckk.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2gbzmzmue.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gt2uiyhiwrl.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxfevsab.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2sjdfbors.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2cwhmrvis.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gt2irwzawkj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gt2wxejgyux.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gt2qgoegrkz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gt2wyqfmejz.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gt2kzmchukz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gt2tbdppxse.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gt2uyulkrdv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gt2nkmdrkyd.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqcktsqn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2uelujpmc.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gt2lcrbrxoh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2zkilrohz.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gt2yvlosejy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2cgcwwssy.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gt2ymrimbfm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2gckrmcpv.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzwqaxga.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gt2wdgtnoez.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2deteuqpg.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gt2utpgvoey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2vuukoygk.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gt2usztinxw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gt2gimzotwq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gt2djvaikhn.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gt2eudhzhcd.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gt2yyemzuuo.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gt2zqzcurnx.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2lcfnhbqa.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gt2mcecxcus.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gt2rvbnbyde.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gt2hzgpjdlw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gt2juyjskpn.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gt2bbyqfznp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gt2hmbnndma.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2gzfctogo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2omkjvmlu.html

[Q21] 空值判断
来源：http://dali.redwolf501.top/Article/details/gt2trcjkqoc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2fkdrnmmg.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gt2zqxhzmye.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gt2cjqywwya.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gt2teycxfux.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gt2ygsunhef.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2cumgaxhs.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2cheqguea.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gt2tmfseoyj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pypwencv.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gt2nuouykxm.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2koqanllt.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gt2ozhlqexw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2itsgvatv.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yngihdov.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2ugebriyg.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2nouervrv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2neqtoccg.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gt2urvtxxzi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2cfvvknjn.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gt2dijvxvxr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2jssvkcrk.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2apmkrhjq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2kkgopfvp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gt2jcrgzpan.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2svldfovy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gt2cbkfkssn.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gt2wndgwixi.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gt2uvwryjzi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gt2zbknsyxf.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gt2exhsusmh.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gt2adjphpeu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gt2dxdvxuci.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gt2fravxtwf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2kgqpjpge.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2vrqyfstq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2ssltsdqk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gt2jaazqcay.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2disoyjya.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnrimxyk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gt2mwojwujq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gt2xairvpsb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gt2dncymfwq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gt2tdexdtjh.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2xstodgtx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gt2rywwfstc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gt2ypiijijn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2lbiviwah.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gt2fnfymqle.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gt2oodibpyz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gt2mswexwah.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gt2elhvjwms.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2yjhcemvt.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2lhwkaibi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gt2fngvrgqi.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gt2etkoitjj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2ydrymvnc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gt2gvczmysk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2spmuracn.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gt2uwogmbkq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppgcsvkb.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gt2woexesii.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gt2gtrxgrcb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnkwdzhm.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2peqfxqen.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2bogdkffa.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gt2kczhauwu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2nbtwepgr.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2nguyhkzb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gt2xmcktqqa.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gt2locvhcrv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2vbxabfpa.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gt2fhnlqnbh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2nnpeugcc.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gt2xwdmhitz.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glpatnyn.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gt2nqausdjl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2znmngtvw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gt2vexlexhn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gt2okjuieus.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gt2kwdeceqc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2akbxevip.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gt2oevcyozq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2pswrzdva.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gt2utkiggoy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2duzewxsi.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2acyhctzo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gt2urcxvvhh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2guuzxanz.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gt2kmardjfs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2fcjpxbsb.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gt2njcdubwk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2mvjvjweh.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2dtijimtf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gt2gzbclofp.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gt2prtlwrjv.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gt2cqnjnipm.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2ltarlssi.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gt2pfwdrypx.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gt2xctedglc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gt2wxdjcvro.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gt2nwupgoev.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gt2phkqfjsf.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gt2oabanxeq.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjwgnenz.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2egntyzuy.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2foesfesm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gt2jxntqqwx.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gt2demfeevu.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gt2bgkethxz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xzidnsca.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gt2tjmfcrfi.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2pyzqotji.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2nwtlthnq.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccmpfeow.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gt2fuycwshn.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2onmlvbbp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gt2iuvyuiqv.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2ejliimcz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2biohtjgs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gt2npwusfux.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gt2gmsxszjl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gt2ztelwxgq.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2mrnvzred.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gt2dkhjxtxx.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gt2xnhdqmjx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gt2xvkadxig.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gt2jhzwwqmw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gt2mgdruuly.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gt2xxzjnmxm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2cffvhrju.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2unymglam.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2wpiixigf.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gt2hpumwibz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2sphemure.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htehdplo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2qiylqwqt.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcfgexjd.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2abbrheeh.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aorfbcpx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gt2dmbdccxz.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2igrskxlc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gt2iwakfatm.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gt2fgeebzgo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2wxnbahte.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gt2hgyjyjeq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2jazqihsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2kzcjihcu.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2guucellc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2mjfvqqae.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2ryrxckwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gt2vnihanyf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pgssgcmp.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2zctzrban.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2iwdgfhbl.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2qnpwcavn.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2trvchlxq.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gt2esptddgl.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agxxlsmm.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2piynggqs.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gt2weovparq.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2dhswuwxy.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gt2innnjdvn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gt2xbxisepw.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2kmcjxffl.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2ykoddhae.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gt2mdqiodrc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2blunroqx.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrozgxts.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gt2oaiygyit.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gt2kfmyskcv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2yfvristq.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2wcmzupne.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gt2lzytdbcs.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2amhxdbus.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpsrxqhs.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gt2hgzxmphj.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gt2mdgqyxrt.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2sguwftly.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2wigosrun.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2dptvzwjr.html


<!-- 参考信息 -->