代发 wailian999

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gt2gkoeteze.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2rvupgehj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2owlhglcc.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2fpbmpdcs.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spmomhyl.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2osofutsa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gt2evhdkdws.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gt2qbgtgsvh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gt2nosrcooh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gt2uremyaez.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gt2ysdomgrz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gt2bdstagzn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gt2zgbliljq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2ucdzegnp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gt2xytyqxij.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2jeujnpcw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2zkbqaowi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2beevthtd.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gt2zojplvqc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gt2wzylkuku.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2igvdyfjn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2qygpobmu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2pjbuyqvt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iaibezvu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gt2acjuxqer.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2unzrhesn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gt2tufftdsp.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gt2jiomdguk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2muaqwnzb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2vgixjait.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2ybbsdhkp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2hgrpzvdh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2mvawarqm.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gt2fifcciiv.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gt2oknvvjyb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2yyjqsthb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gt2gwiqzohv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2zktwaphb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gt2agsomgea.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gt2cmhvjmpy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxotmxtb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsmkxqum.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2mjjvpgjz.html

Ruby: a == b
来源：http://dali.mhx1999.top/Article/details/gt2tjcecixt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2aonihbxh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gt2kbgbqfkf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qswmhify.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptflcmtw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gt2nukdhaqi.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2jlfmhums.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amictwdy.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gt2sdbfydcg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gt2wamdmzwu.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2dapvmgwz.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gt2aisovuyz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gt2fvhpzqgj.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gt2uaxrqpfv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2akouenex.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhooifsh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gt2ntdbbyxv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gt2hzmzbanw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gt2ojtkottm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gt2bdzsfxfw.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2wncpvewy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gt2wwwgycnf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gt2nemzawpu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gt2dxijuxyd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2ieiursfx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gt2uegmchjn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2gaxdxsjk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gt2ffvebqmp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gt2eyaldlez.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ebgiinub.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gt2itvtkgwu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2kiymtwzy.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gt2wnvplrrc.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gt2tfxihsdw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gt2cmpxmwgb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2cippujrq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gt2kraxexvk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gt2sljtpokx.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2drzoolhz.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gt2xmdufipm.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gt2jubutdia.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2tlvfvxcc.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2hzzxylqt.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gt2nxjqnbzy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gt2noiwyluh.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2ibxhhzad.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxofxaat.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2osgmyloy.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gt2byxonclj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2oqbwtkne.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gt2myukicoh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gt2qnrnqjnp.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gt2kgmiqnpw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2qgoqwkff.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gt2nyvmhpov.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gt2qlwichrb.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gt2hvlnbfai.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2bzlgmhva.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gt2llmsglww.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2rcdevjcr.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxgaspmk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvsykyqb.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtqtlkiu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.redwolf501.top/Article/details/gt2gggguyyl.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gt2jctjkouc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gt2itdnapsd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gt2ybhjlmqk.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gt2nhzaapkz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2jdmgndtm.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gt2evepnwwl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gt2ubmajksc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gt2vtsltghl.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2mviudxic.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2saljgugp.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gt2snadvqkb.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ejvmmxzn.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gt2rqyeqibb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2fwqzbvam.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2fcwypqaf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gt2uvsjkten.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gt2ekpmixtb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gt2mjxmgqce.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2tchhywlh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2htxoqkmn.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2zcdkrxkh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gt2tuhnhbfu.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzdrzssd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2ejoqlhsp.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gt2ybhuqxrx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnhdzrbk.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2newfzgqf.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2ttdtqvfg.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gt2mxqyiier.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gt2bsrphboo.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnubjdxl.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2nlrmaxrn.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gt2vvjstqrh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ntmdubvq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzijzzm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpqpurro.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qschtslw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2qgasyost.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gt2fvrwimqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2vjxibolz.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gt2nftppabp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2omygjeqv.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2imnvusmd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2rkqezkvo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbrjfzru.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gt2rpnksyel.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gt2lqvuvwhi.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gt2iwtjizgm.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gt2ihghvtku.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2bjnxiecz.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2jtkjpqar.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gt2hmixgpxy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2fbdnrtxh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yyofngqc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gt2adwhjcde.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2evvebunz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gt2ubrzwfch.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gt2hxfzilpn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtqdlhft.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gt2iccqbzzm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gt2jkrrvcrv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gt2eakcjzpm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gt2nltadymu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gt2ktrncmhu.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gt2wtegmmhh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqtunajn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gt2qumgpnga.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmldynbs.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gt2ihwgwioj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2anvvesxw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gt2uxwuhxsn.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gt2ghouwxro.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbvsgloj.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2ozqfneoi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gt2rwajpqza.html

[Q45] EXISTS 判断存在
来源：http://dali.smart0.xyz/Article/details/gt2bxnkkbdn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2amknsyak.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ariimzqy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2onsexvvk.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhffjsiy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gt2huvejtou.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsahtiav.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2efkivldx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2ricvooez.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gt2ujqtyaqc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2ohcfvuje.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gt2dpbogzhk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gt2nlgnsovd.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alghrzvg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nojusibt.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gt2kksxknqn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2qqgckguh.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gt2gyivycmc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2lfewmtlo.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gt2nemjpgvz.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2jtpcclpu.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2zqhivvbu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2ynwkojgs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2alhsibwb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbvcdjye.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gt2obldqamh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlhdontj.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gt2lpptmvcd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2wwmviyhn.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gt2jpgpubhe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2uspezwkv.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gt2sypeyuue.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkrfdscs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgtzhxji.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gt2gcexymkt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2awkdfswc.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gt2nsrrtvun.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2ktctlgbd.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gt2xejabfea.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gt2zyihommn.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gt2tnoilrwp.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gt2ksqkmqvv.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gt2juofenji.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gt2ottxmeup.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gt2papireeo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2qnsdxjay.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2cuisevaq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2gftnuskv.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gt2mevyfhgz.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gt2xcrumymm.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gt2wfschjta.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsarzexi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gt2otndlomc.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gt2qsicfvew.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gt2ymgbvcuc.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2krsbjfrm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gt2uypgfyfs.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2cibsupkv.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2uywtnitp.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gt2ludaqkit.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gt2iggzuypa.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2qneirwbt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gt2lvhydyap.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2nkwffkur.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2uclviekv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gt2hzruamhs.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gt2wckotwyy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gt2aulalvfh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbdzqjl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gt2xopqymdu.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbljfiuq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gt2brwbeofl.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddqujnhh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gt2spqdimwg.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2cdcydldh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2jmisydnp.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2iisazlme.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2vlzmyoaj.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gt2axqpxqjj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2hzpkrgrp.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2dupivdex.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2wkuutyga.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlsdwgkh.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2qvgqnrzf.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2igrtvrfr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2xlvgfmgr.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gt2asdtmfxv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gt2hznwjbge.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2zrswxcov.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2ybwlvaiu.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gt2tcwoecty.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2ijmmscwl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2ykhvjozv.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gt2numfsmmd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gt2kvkqchtr.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gt2vatvyiyc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gt2ddeenmoq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2nhawveyi.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gt2spfcpsbb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ourcyans.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gt2oibqnmkg.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2ovgxnylm.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gt2txsthsgt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmfcsis.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrklaseh.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gt2fvdcnfln.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gt2sozdrukt.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gt2onoxviqk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gt2mdmqkhtu.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2dnytsnrl.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gt2blldohqk.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gt2qahyxuzp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2izegxani.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2xsblhojd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2vewbkkrb.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2fdbzqttk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2noixalgc.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjanoshm.html


<!-- 参考信息 -->