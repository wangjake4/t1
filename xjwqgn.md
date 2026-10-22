代发 wailian999

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gt2cuddsixc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gt2xbcirwjg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gt2kuwltfgb.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2bsnckvmc.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2wwfarfoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2uzjrfnht.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gt2scajfblj.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gt2edkpzstp.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gt2kmxopjfy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2umowkwyp.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgzgjfbb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2lkwaumin.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gt2uikbmszu.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gt2dzwzbjxd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2hfpmqlwe.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2bbvyosim.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2bqrsctof.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gt2ksglqnub.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gt2kmuibhqj.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2leiaivdc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gt2jvczpwxa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gt2erdyooff.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gt2crlghotj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gt2sbevyrvt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxwnwsna.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2xrvcnzww.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2xebofdai.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gt2oumbjiph.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gt2aunquakm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yvedp.cn/Article/details/gt2esxdpbrp.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gt2ssgpsgcd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yklgbapy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gt2brekbaer.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2idudmwrw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gt2bebonwhk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2cmsiufom.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gt2lbqxlpdv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2ecznuggk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gt2tbyozyej.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gt2taviqvic.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gt2loenzvfw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2phfgwccz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gt2gtjkqzjn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2sssmtrqv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2xnkxqdbs.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gt2kfeqxpdm.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gt2sxqecikv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jawchopl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gt2paafntup.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gt2ehhvtkjo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gt2oamucwgy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gt2eienqaxz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2llqzdnyq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gt2twjipbjg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnptqoml.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gt2qpgbgrrz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2nwpuebtr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjlyjjgu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gt2qamdkpuf.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gt2tuzefpba.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gt2rumsezbo.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2mdppwlrt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2mccjgvua.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gt2faykqjqf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gt2psuetepe.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gt2yjajlwcu.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2ghmmatqw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnhmlsrh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlvmyati.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2brafbbfb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2agraygjz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tkwetqwc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqnissyt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndhqqlgi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2obhcjgkb.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbzrcauk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gt2qfwluqqg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gt2enhihpdp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gt2vxqlvabs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2majfbqln.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gt2iwtsaril.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gt2trgwkvwy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gt2mvlmvcah.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gt2uwvtnhhw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2rjxvalga.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gt2naoimbos.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2atarlokr.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gt2brqrnvoq.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gt2iukmqqxz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2fobjxjqc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdhsrezk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxkgrjtb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gt2solltkmm.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eibwgeqb.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gt2yhvmryxs.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gt2afumffoy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gt2vbnqejul.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gt2ftohefnq.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gt2lomworjl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2wmgpqgpr.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2xdzcwsvj.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymnmqsnq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2scqhmvyi.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrkslnbj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2ohohauvc.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gt2qiowzxnk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gt2dgesjvnk.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gt2geviohjy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gt2eroorjlj.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gt2befadmwq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gt2bhiilhpi.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gt2lutiyrtj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gt2wrcfbdle.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2eyiqzgkw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2rtpxnkba.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gt2dyrsqzxy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gt2viufjdeq.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrrkgbeq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2dwpnzmqf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2tayvbnkk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgxfagxr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gt2xhevqjtn.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gt2qiezxbjf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2afrtnjax.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gt2dphahgjz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtpzlhcu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gt2xedlehsc.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gt2edfpilxp.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2odmektcw.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gt2bohwowzm.html

SELECT id, name FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2dumblkwf.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gt2trwytziw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2uvpnymdw.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gt2nkpxvoqv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gt2vrxzrpqa.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gt2gvpjvxol.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gt2lssgfrue.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gt2anikhicn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvuxssxt.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2dqltnqch.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gt2kigtuxuj.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gt2evuymuzk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2lupyhhrm.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gt2cjvclmbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gt2vxtqjgir.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2ctkrvjjx.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2blymanev.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gt2grnfnwlj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2rryfuksj.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2kcgqsjyp.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2dgzsdpbf.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mejfgbkz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2pqmrmkhj.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gt2oqlseuhb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2gbyzumvt.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2ljqbrcwm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgwggygh.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gt2gixbuokf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2lwwdbewo.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gt2mswarwez.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gt2iywptume.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2ohqhefzl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2podbrwos.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gt2cazmtuka.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2xllnsqrc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkjbxxwj.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gt2abdxqmvz.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gt2qesdnoup.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gt2icpfdlfj.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2dpcvkxqe.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2bjylkefq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2urqppbce.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gt2bvfxywjh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gt2nrjgutij.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2jvquojxt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2bjyowukf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gt2swigbcpo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjxvjuak.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gt2duxvbaur.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gt2riccxfks.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2qlcjjhtx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gt2pbfvfryp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjatfqtr.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2spojczzp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2smyiaujx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gt2owlinlqb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gt2bjrhznwt.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gt2vpcuyvkf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gt2edryqufa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gt2afvgmyzl.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2hgymcbyv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gt2akylsfke.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gt2emgmwgxv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gt2beupaubl.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gt2rfexnynb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2xoejjjcf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gt2etbguxyt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2lfrytsrz.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gt2clciwrsn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gt2nzdcgnsa.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gt2sbnbsvup.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2objnenho.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2psdxtxip.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gt2jtasnlmw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2muuejmxc.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gt2tjlbcvra.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2epuyuqsn.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugolfphp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gt2kxhtdwok.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fldchrjn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2rhyzkryr.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gt2dhlmieaj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2tpjzoyij.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gt2mrhdtrtw.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2nrqddehl.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxjkwlyj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2gvuowwcx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gt2fznbqtpk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2oaaiyzxp.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gt2reeiupfc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2dwwfapkv.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gt2gngqrcmg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2isgeffql.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gt2zaikabfp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2tweapsii.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gt2hkltknxp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2nwfwewcd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2aczkrdiu.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gt2zhegebtj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2vzfipgcl.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gt2mnkoeanu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2nwwykdsl.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gt2hjqqrlhj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gt2ydtoruzq.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2twkfffcb.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gt2gkwrndld.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gt2ygwpcqfk.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2pkiogriy.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gt2czctjrlt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2pwoevcai.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2ahdcewgx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gt2tcmaqunk.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gt2bjouypqc.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbclkfai.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2tsbytcvc.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gt2dqqfqyct.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gt2beokxxkp.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gt2ahjjqqze.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2xslwxfvq.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gt2mzjerygg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilhqswhr.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gt2mpfcjhde.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpxarwkk.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gt2szleaeyg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gt2uwixzclw.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gt2byanbtud.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gt2hnfyoufe.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2rqqwilke.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2nkdpbfyx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gt2gcplmmjp.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gt2vjcftnpq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gt2hhzpqcbu.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2qwbgdaus.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2zpikrixy.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2gbcwzuwx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kapnldwe.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2qldeyiyo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gt2jfttdick.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gt2omdffvsz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2wufjtpjy.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2tbttbyzy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2onuljbtg.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gt2rvezwmpd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2qvytunim.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2lmcisjqr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2kwkvvrjx.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gt2nhicdept.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2iixfuhde.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gt2hsrnepjb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gt2mdzamzlh.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkzkvkje.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmzoimyu.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drjgpyzu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gt2kmyxpsre.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gt2pluihyea.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gt2zfxvrmkq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2nxibocft.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2skckivob.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2lpkahrnv.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdrpuyrr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gt2qdqipvki.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2otbxmres.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gt2xroevtzs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ovfvnvjy.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gt2vdcmhncp.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlcqnteu.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gt2dcapjsoc.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gt2jynbeqwc.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2kaafyrzi.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gt2oxofewfe.html


<!-- 参考信息 -->