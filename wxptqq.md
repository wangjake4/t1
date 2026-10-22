代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdjvderc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2myesthui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gt2qrvmxbzo.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2polvrtnt.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gt2xvlmxjjh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2bnyeevep.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gt2qctjjypi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zktkgjgg.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gt2puxydocd.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2foxmeivv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2cubmdsvx.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2bntvdvqy.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2wedfigzr.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gt2frdkegrq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gt2qazctwqf.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gt2cdizrhnc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2pmjydmqn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2vabkpfod.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gt2yuimarro.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gt2rczwpebn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2hxothbhh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gt2epeqzbdq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2lvdegcdv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gt2fvhipnju.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlbrryoq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2etdffxyy.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2ywbpvnec.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gt2vfphdxnv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gt2mfewlpqj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2sgflpayr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2orehiofo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gt2wwgxtgfz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gt2lwacwien.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vefastps.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gt2qnclivdm.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gt2pkdewwhu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2hctzwmsn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2zaxkplbd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2owowdfil.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2byupmqob.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2ajlrbnxj.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykwghscm.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2ipfgqeyt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gt2ivloadsb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgbrisgn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gt2rkfbnuny.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2folptlrg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gt2tejuzozf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2woudenqv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gt2dfmnjcoy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2dtecazji.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxaodmhb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gt2kbiffezm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2qljaivxn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gt2wbxhaxqx.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2xjgouoag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gt2yuqxyxni.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2wnyjvtso.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2mpjxnutj.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijdsgijy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rajqkexm.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gt2cummcfpf.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2yyxvcpad.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gt2hmeyrvac.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gt2ndqfdsgb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2zytlhxiy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2keboxjlg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvhsposm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gt2yduyefbv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gt2nohyyrae.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjlgozpt.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxunebzv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gt2hrflpcls.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdoyhbta.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gt2nugfsehu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gt2tjrxagge.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gt2wpjbjtbx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gt2ykzzwwbp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gt2acmdadqv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gt2puuptzfq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2gybcvgso.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdsamwle.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2emowqlhu.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gt2aslmzjeq.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gt2pwxsdvec.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2puzhzbxf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2ydoavqvc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2tpgycfro.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzctgrpn.html

);
来源：http://dali.tian-w.cn/Article/details/gt2algowzcl.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gt2zobvlpah.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gt2lkaabzdi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2tahacguj.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gt2hgjfwxur.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gt2sogxdovh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fysgwidt.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2kvsqjeya.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2fulnbljq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gt2innejdcf.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2clmgdtgl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2rhuaeveb.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2rcjtetfz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gt2mwzflaef.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffhylczd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gt2edzadblx.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gt2qhzyofgk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2jnxduhnb.html

[Q08] 创建普通索引
来源：http://dali.jqgufenzy.top/Article/details/gt2advjlihu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhdxizlp.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gt2gisakfgi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2uftupqif.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gt2wetsfdcw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2hmcpdfgc.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gt2ayxvnbhk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2hiunyone.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gt2mswrawey.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gt2tllcbpxb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gt2uksttssr.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2loqngppo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2vvqcalxv.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gt2aschdtiq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gt2nrakluic.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gt2rptkkkbj.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2igwlmxhu.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2nigneakx.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gt2crtkpugn.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqikcmgd.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gt2jcmxtbnf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2tjfgwmbl.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gt2ddzcrrhy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qawzjrqn.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2ifmepszo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2hqchrour.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2mdxfurje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2svtpycyu.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gt2arjdcpkw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2ceygbfsm.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gt2yvxtqtdx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2irrxeddd.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2yqeftdvx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2nuqjrjwz.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2xacgepos.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gt2kbvfdeqo.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2rlfxzrsf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gt2ikccbykg.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2heaqvyco.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2greeknah.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gt2dfqqiivg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2bgvshopo.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gt2vvbejrhj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2odwnvgps.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2yorjobxz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2wnpsdchg.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gt2tvsbilnx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2gxjjntml.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gt2fdplvqfi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2crqstyfb.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2mifkvlep.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2jsdzibmm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gt2qspdecin.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gt2abswxsnb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gt2aguchfvf.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gt2shksjzek.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gt2fhzthhzw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gt2beuxrrwd.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2ucgxewky.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gt2wahxvxhj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2hhzwhwpi.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gt2nokuiwet.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2wvoxnqho.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gt2hlksudxf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gt2ncnizump.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gt2pfxqybjo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gt2jryrytbd.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gt2vdacfefp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gt2vlnpmnbm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gt2zyqzitxc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gt2degbtbtu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gt2rpsgdhei.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gt2gzhxnzyw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gt2nxabjtun.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gt2slupgbps.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gt2krbzqmbp.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gt2znsckyrw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gt2esshzmvn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gt2zskaourr.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gt2xplgtmgw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gt2duauuhng.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gt2bktuemja.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gt2sfpmjauk.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gt2tbvjscny.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2doskexxh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2zlswqlgy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzyoatec.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gt2jogentij.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gt2xnplsszy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2uzimoqjv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elbsreej.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gt2dauqigmo.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwfobnzz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2errpltbd.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gt2ayfqahgw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2ancptugp.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gt2xkjzgtnn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gt2oqsrcdyz.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gt2zoyljywl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2iusganjg.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gt2vpgqndyj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gt2skwoscbs.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gt2lbiwflhn.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gt2dgcpwigv.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2zbdpjmij.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2omqzpuig.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gt2nooqlfuo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2kozffrso.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gt2petmvcpt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2mslxgwcp.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnmqorho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2tuxcvdpm.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2ybjoqtjg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2tvrzufcq.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gt2mavibufj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfmrhxvn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2ovzxfbph.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gt2upnfwmjy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2bojtprwp.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gt2ztrhixbj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqotzaux.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gt2hdnbhmyu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyrjjhmu.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gt2zywpvebo.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpjfzmhk.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2twgpzjjp.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gt2ntyhtzjl.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2cigzaxvr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gt2wboqicqw.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gt2ghxuqmbi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gt2lhrbnaqr.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gt2xhnxluxa.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gt2xizxoicj.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2fiwafhkw.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gt2ihsbzqiu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gt2gipwveka.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2emuniajb.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gt2ilbvcsis.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gt2djwoimff.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gt2ooytapnp.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gt2ykghvcyc.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2hefheewi.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gt2wjfzzucw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gt2opxwhjso.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gt2otfqfyqw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxuvbcyt.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2nvlqjgiu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gt2nieeaagy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2lahcjjug.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gt2rqqvlzmd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gt2gqskfxmg.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gt2gxzrondz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gt2rqefffwu.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2kwxnbjgr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gt2hbxsdufr.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2dwiyfigt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gt2ymshvqee.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gt2cbgqapnm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2lyuxtdog.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2swbpgfih.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2iggxizic.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gt2qwmeaezd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2xrbcfxdv.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2ezxpfddp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2vrgpvgxj.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gt2zkhrycao.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2xqncyvmw.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gt2ehubriox.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gt2bahukuhl.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gt2wirlpgxi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gt2czhomumt.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gt2cgngyqwx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gt2xeuwyjmw.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2qnwbrcmf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gt2vemttchm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2mxhyttbb.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gt2eovkaudy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vynibije.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2zexxkzsm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gt2ozjxmwyh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2gmklzoui.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gt2kckmojmh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mslyqvru.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gt2gpvnapvt.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gt2jbmkombk.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gt2hqzxyvmn.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikpwisaa.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2knnqcyla.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2xddmrzul.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2tdwsyoms.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gt2okvxpbdz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2ruketjnj.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gt2cszhgawa.html


<!-- 参考信息 -->