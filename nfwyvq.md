代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtaqrpbfrm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gtllhcyyfe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtrcruboix.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtiiqhuwbv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtolqgknah.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtyyxsvamb.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtpscakssg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gteyildozf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtmripsaob.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtqgrzgvvp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtrypmdqkb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtsfkoszpp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtloytwtsv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtdfbwzxai.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfptdjsd.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gthpnvuyax.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtmuntxajp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtvzmmevtu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtcybohthn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtjolikinq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtpzayhecd.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gtdmshqhlz.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gthjioykcr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtekasnfwl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gteencevxt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtqmckscvn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtkepmopay.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gtndargztx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtsakrultb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gticjciidt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtwzzwbpox.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gtnhfkhuhv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtnhgjclln.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gtzikmdrur.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtshqhcmim.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gtulcwdrca.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtofmypidt.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gttebvchjp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtxinlukgt.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtnutnzarl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.quarkkingdee.top/Article/details/gtasbfgssj.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdccexhuu.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtsyxazpjl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtubgkqoyj.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtfeivkunx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtlnhxoggq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtjwjvvzpm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtmzshxidv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtyzazcarv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtpktltxyn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtnqfnwmhr.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtqringidb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gtirgouioh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtlvdekszy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtnjaxcwii.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtqicbszwa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtmmhdzdgn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daxiang520.top/Article/details/gtppslvxrw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtbpdwdsqi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtyccrysus.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttbtqxlcg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtpofxtcau.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuurfajpv.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gtstbapmgb.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtwxjfgicp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtufxksabb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtihrhfgvk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtflatmxrv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtzaowyteh.html

);
来源：http://dali.zycfv.cn/Article/details/gtrxsmfwva.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtthfrmowe.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gthovayggt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtnigwmmzc.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtgxlwnklq.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtlsirkkws.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtzlyiitgp.html

);
来源：http://dali.snrcjt.cn/Article/details/gtuopfifjd.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtvxhfyoxu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gtawazeowp.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtlicdlqui.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtznxcywci.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gtwztcyuab.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjvyhnbq.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtzasynfns.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtpqeokxjz.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtvspgearo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtavayjhir.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtrmwelbxe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtaontjhog.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtonxihnws.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtgonseynk.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtwnygbgzi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gtsdtubtiy.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtainhlemv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtrrbgrsik.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtvpljigoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtbhrrjetx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtrxvoyrje.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gteczwapey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtslwqzfng.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gtxgmijytt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmdaagsx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtunwztsiq.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtnsrxcboz.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gthfjpxgty.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrfoewms.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnldbuztx.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtmnynsqsg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtstrwtpdd.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtsnmslukd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtpdmixwoz.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtaiqybarb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtgoeqagxq.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtkolkzeap.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gtxpvqabhr.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtquzaotcw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtqgygswol.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtymmmtxzq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkfbrjda.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmljsfdg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtyikqpwoq.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtauypxbwd.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtdurbtzzs.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gtumnlvstt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtefcvlhtb.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtcsixevyq.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtcvntbnsg.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gteepgnqut.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtatzjtkvs.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gtxlomkrfi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtdjterkja.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gtennxtpou.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtpppogxrm.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtuawatkbw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtgimsxosp.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gtgfakdmtj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgdziczu.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtwtzbndig.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtfofjomij.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gthdvkabmm.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gtxjlskbep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gtwbdofizb.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtrqwpzirs.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtxcbdwyda.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtfaiorues.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtojcaekbf.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtoyxxkuwd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtablpdqny.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxeipqkt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gthepwwbjh.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtyulowpxz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtmyirljnz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtyzkhrbvm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtrwvujtsq.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gttkfhlppu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtebzlmriv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gtpxutfztz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gtceisxqyl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gthbmrwoew.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgribflmo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtlvlsjaxz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtsddcjaft.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtdjmuiper.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtjpwwwnzc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtppybwdew.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtfazmprwo.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gtykustyqw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtoxpwynar.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gtemyvyadc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgdunyxy.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtonqmgzev.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtgmulhxue.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtnvtbdmge.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtdaeebvuo.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtohuorvoe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtadyrvzpj.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtrhsqnszf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtqamhcngr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gthjrkcdok.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxqbgvaj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtgekqlkpj.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gtgbvvyluj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtviazynem.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gthhtsjyzz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gteogczdbj.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtiirnzldb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtvytvuvff.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtfskexeaw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtvcvqiipv.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gthrhdklms.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtvtqwougf.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtmkmsobzs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjolsegaa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtidggfauo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtayhumhns.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtbwtbgynj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtjmtobwet.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtnfgcpnvn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtrhckkfjl.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtestkvqzw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtdcvyqbeh.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtjgolfkwh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtoismjsyi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtlyrlmhwz.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gthreawofb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtvysfpkzz.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gtgyfgpnzp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtprzfeuaj.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gtgltnjxby.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtdluxxanl.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtccqpgsrw.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtozswnwyb.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtbwqcvhwk.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gthcbskwgd.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gttuniekuw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtacpamdcu.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtwvcrmylo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtswxirxbd.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtuxbgxqfo.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gtqvmbquin.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtkkfhjxzp.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtovupoums.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtrpiflihi.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtxmjorlkz.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwztthvsa.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtdrzjiswk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtxtqivfsl.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtymgkhzid.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtnepvzjud.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtuyxamlbm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gteriyrbhp.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtflmjntgi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gtrsoshfwh.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtxahushwt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtcbbsyybc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gtkhgyzfnt.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtzlplzenn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttacwnkkq.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gthwbizwuv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtqcnfecpc.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtrxzszper.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtuycwfzex.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhvqymck.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gtafxaokrw.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtauriqtyx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtdouetoxs.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtjfkxgzgf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtsxszbelv.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtyeammdpj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtoxtansqv.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtkcbhqiob.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtucwkqfcv.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsleewezm.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgawpwhuv.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gteuqikzic.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtsppjcdxm.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtdygnzajx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtmvcsdizq.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtxopuynue.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtglryijbu.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gthwbwldhb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gthxsetijy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gthrlepnaa.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtoqkpumhk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gtgbcphfbi.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gtmzkdcswj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gtikfzglqa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtersvrqns.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtslzjrkaw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtelgifvzw.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gttyzrdhci.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtubrwidhs.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtczzikerq.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtcmlwqnfh.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gteamuahsn.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmwgopeo.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gtgjvvtggx.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtecqrrivj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtlestfjnp.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtexezrxgv.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtrqwrvase.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtkvnoiyii.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtgavatmcy.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gttmwvgfac.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlchtevh.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtpmtcpzyu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtzzfhwkzk.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtahfekmro.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtclfyusmw.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtyguocoov.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtfprqmksc.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtrjlziafk.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtorblgvpj.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtckzcorhc.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtahijjcej.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtazrznbmz.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtfdmjuhpe.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxbxnjwa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtdeavcmpy.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtehgupslt.html


<!-- 参考信息 -->