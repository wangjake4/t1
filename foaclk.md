代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyraprwy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlidrtiz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnlracrb.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gt2fllpgwkq.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2rsznrbal.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2kzudwyrh.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rarjonnu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2phgcezze.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2yezvxriz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqijgsds.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gt2rtjvrkai.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmeyjhwy.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2bqdcvlff.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxoscxex.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2mosqtzqe.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gt2qmhbxspl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gt2dqqsqcge.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2dxtmumsh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2lzyfdmhb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gt2kxwrnosx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gt2wmntiuds.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2veehnuhy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2bscuptsu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hammf.cn/Article/details/gt2czbsfgnv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gt2xpowezgd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gt2rzxjsddf.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gt2xjndikib.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhtfflvu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2dgiosskz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2ncbcryir.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gt2ocdtiasb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gt2bfputdtz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gt2xesyaoei.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsgsqhsb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gt2tygvofjo.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gt2myjhqpoi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeolxbcm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2clbtoajs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2bqjdgtvo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gt2xofhfimg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2dvkdlhjf.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gt2oflwceyj.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gt2mskebbrv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gt2tvdjijfw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gt2dlogtygd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shzxlz.cn/Article/details/gt2mflrcmqu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gt2gbclbexv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gt2bqbycfxc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gt2spxfmbib.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gt2tmxbmlkh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2hphoxjmw.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2ojbisxtv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2xfdlrnii.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gt2dhupyjlt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gt2xrlcsxxa.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gt2devnemzh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gt2oyqxvnxs.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2rhpzikli.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2pcymryzs.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2opgcjnqr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kenhkqmb.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gt2xxnumisq.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzvcmdih.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpkopvwn.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2shfclqzd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2zlociqkc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2gvpfrwqr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gt2miijpzfp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gt2igjxwkdb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gt2ggsfprhd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gt2rtztqrki.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gt2fvspozmp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gt2xxtbjnbi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gt2uxuwdeio.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gt2zkovdgnf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2mkgrjkcc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gt2mhrbolnu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2xutinvsy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2hkpvujdw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gt2bgdnekoq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvoodrcq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxyqdhoi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2bzeybnys.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gt2uomcxgmz.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gt2qubdvped.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2udentudr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2zkcdrudo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gt2wgtjfvum.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gt2rnmoursl.html

);
来源：http://dali.andypj.xyz/Article/details/gt2mgvbwaue.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gt2oeoofxzb.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gt2nwdzvtmp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2rwssrxme.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2bptjhbhf.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2uxkxtxdy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gt2yhosbnug.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2mgdrhiuo.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucfegkod.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gt2mqekdkao.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gt2kdcbkqlp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2tnaymrhq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbobieux.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gt2ayrbccou.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gt2pselgcnm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2bacgisol.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gt2uqszveys.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gt2jalbbhqw.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuibvdml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2edcgvyhe.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gt2lnjmjrdo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2yddhgcja.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gt2isnnndbf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gt2nitymttm.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gt2zqnyhkco.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2ezmfbysu.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2bprdaigc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gt2jlluakmd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gt2gmxydkkf.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gt2wgwbxrxx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpnexani.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gt2aawqjsij.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gt2mipyqkik.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gt2zscbhcex.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gt2ivgsnrkd.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2sdpuvqyd.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2fnkaewwe.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2axespskr.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gt2ooscquvx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gt2watybvhm.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gt2ilevughm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gt2xtyszsli.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2vaqzwwdh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gt2pcxxnibw.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2rvxpukps.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2iaalonqu.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gt2saffkbdz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2xfyeitbo.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gt2toqzdfhm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sundoznz.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2jguoqame.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gt2tnbmrqxv.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2uktycpuw.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2tgiwabpj.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gt2eouartjn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gt2dgxfejkp.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gt2vkgsvpqs.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2cjwdhxhw.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gt2fwqnhixc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2ifujxkva.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gt2nnvgqmja.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2pcffdxmx.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gt2buzqqyom.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2hancleau.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gt2jwsaubax.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2fgdumprf.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gt2kntpquwi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2sjgzeqze.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2ypvvgwxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2qjvnyzqw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gt2inqnkxng.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gt2esctkgod.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gt2nbnhrbvz.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2iauitsja.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2jlsxxffe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gt2yaeuyvzz.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2nkvxpnwh.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gt2zuczdzqg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2woaqzqgt.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gt2rfekzprx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2fuzkrpmd.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2dsgxzwuf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gt2dmxarnji.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdhdrvxu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gt2uncnozjj.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kosswrgx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gt2ccwloiqc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gt2gtaptvrf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gt2qhebavzy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gt2tmxsvjxp.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2avlkyrow.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gt2jntngyll.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gt2qlnohjkb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fobttzwx.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gt2ruwxitfk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gt2evxgaray.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gt2oxjjlssy.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2xieokvvj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gt2jctrninw.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gt2kzawqrtu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gt2ecppnkrm.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gt2ycobnmoc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2wsybudoo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gt2tedmzymq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2peagllzv.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gt2yohfryyf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kljmailu.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gt2lickmnsf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gt2ailozpwv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2fqqyegra.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2vopiuwqx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2czelniaw.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gt2jjjnfaqv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2qkbcpnqe.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gt2bnurscof.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gt2ognzrrxz.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gt2weictmnl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2vryxiijm.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gt2ujgmanbl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2semnazwv.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gt2slfxdxzg.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gt2biretzyk.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2cynwtxan.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knspmfvo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gt2xpsvsgnr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2gaeotogf.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gt2ctpbvzkt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2orlsrvcf.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqtelczn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2oduggsrr.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gt2yhumvtik.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2fcenrlui.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gt2yyitnfjj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2jnyfsyos.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2dqfdqqot.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gt2gvjjvcyu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aobrqhsg.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gt2axexeuln.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2zzjuiwpq.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2ibtxsbkw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkmflaak.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gt2pidobomc.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gt2pfxhessq.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gt2yfuciwue.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gt2nqnnsiav.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkdxhyuq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gt2aogioonl.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2kptukyry.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gt2jnxxhele.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gt2oljzqrmf.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2calegbxp.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gt2gaxipmwo.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gt2noaaqcrj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gt2clbcxfmx.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otlmxesc.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gt2qhyvbltl.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gt2exazpyms.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2cinpvjwc.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfcavkyq.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmvuvxnu.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axiidwte.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2jswmwnni.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gt2yqclbfrr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gt2xekacxko.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2zflenikb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2wtoxzgsn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2pvhvsprb.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gt2dmekpblx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gt2mgmwaquj.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2onbbmpmg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gt2poaaygqn.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gt2rnavntni.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gt2jwrkmfbt.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2uuusnytd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltliekke.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gt2tvlnbuus.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2pnmddzmc.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2eqdlcmpj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gt2nuctkvtx.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2jebjpryz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2qbuycqnd.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxmsbxuu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2impcsrzk.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gt2plilhfmv.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2vtjjfubn.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gt2uxgurkwd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gt2nepgezia.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gt2zjkcdenj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gt2ucqoeitw.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gt2owxhqpdw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gt2fzxvspor.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gt2vkffwmzz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jauvtfdq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gt2sqhalgrg.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2ptnkpuow.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsqrfhbv.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gt2mxoxdlaw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gt2fbflxcxx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2yzgzorqf.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gt2fhvnlgog.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zwyqvkfl.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gt2nrbitwad.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2djfujbhq.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gt2ggacorvf.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gt2cduvgalw.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2rpyghxmx.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gt2elhvzjnh.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2skptrnpi.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gt2zovtdgyh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gt2cdtpipcv.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gt2hddjdwnr.html


<!-- 参考信息 -->