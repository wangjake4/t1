代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2qoqiaytj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmvbhpku.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwrnrkzk.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gt2naowsgqh.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gt2vndvxwbn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dqdojgvg.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gt2cenqcjde.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2pfqjjmqa.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gt2jeitdvak.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gt2uggqzigw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2ibdocqaa.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2cdnmqqry.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2utgrbxkb.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2bdcbsoky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2rlgabvkz.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxpcckii.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gt2ziuqkjxs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gt2atbhkyfy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gt2kyjnlkyf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2nkcpeomb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2btwdxucw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2chkwvmgk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2uriryfgj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2fkeuprof.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjzkeeug.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gt2tdbqhphe.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gt2qswiknbb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gt2oqprllkk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2fsavggna.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2cxcqytaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2vzikqiol.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2vbfsaevn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gt2hyjrprkv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gt2bjolulld.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gt2nxszjmpw.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gt2hyhfdrpw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gt2vqwitfiy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2vugklsol.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gt2jksspfuj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2wgimetay.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2vlpafwmb.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gt2iywhctmm.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gt2fnucbihd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2nqwdtlkf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gt2cceqwfqo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gt2ahpzxpgp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gt2juzatpil.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gt2oyewyhjk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2zitjnlrv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqooevci.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2sicedjrf.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gt2hedytxcb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gt2isulnwey.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gt2eiktksfr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gt2dqbwdvzy.html

PHP:  if (empty($x)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2scvkmwdm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gt2emwygbac.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2dbcqlkmg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2yorqmepl.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gt2ajpuhonz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxsoermf.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2tybdapjg.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gt2oyffodgh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gt2iycmmzqp.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gt2nhmrzfwa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2pfhjfmas.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2qzcrmyok.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2krgnxzhp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gt2jbtsiyzn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cucudq.cn/Article/details/gt2hyjkqpiw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gt2goclltra.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gt2saqrmytg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2fmxoicfi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gt2yxnzrrjj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gt2ldyokycq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2rnhygwae.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chjetudi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gt2hmeylshe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gt2oixnesly.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdqywuci.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zodpeqlw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gt2zochaoyr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2drobvdda.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gt2dynencbf.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gt2podvmirc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rizlymkr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2izhxcdyk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gt2vxgzqggu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecghhspn.html

);
来源：http://dali.tian-w.cn/Article/details/gt2qrtosxgs.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2cipbxhim.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gt2stqvezcw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2iljkbmko.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2ubtrqddj.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2jdnkebld.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gt2svmkciaa.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2zlkclzow.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2nmanuepk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2vboetdap.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gt2zgrerzlm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2hsxrtkmq.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gt2nqpsayfw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gt2qfehiluj.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gt2pfjqnjyr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pytbtulw.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gt2rvztorhq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gt2frinfpvk.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gt2buxeygth.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gt2yqtnfucm.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2myndcrrb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwccfic.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gt2ivemqgnq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2mzfmyane.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gt2aqbhgban.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2wmmfbrui.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydglqbnq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gt2srosckdr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iclgurvb.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gt2ciarusut.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2kfrxcivu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gt2nuhvgsqv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gt2hpsauwhn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2ucbhimyf.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gt2vbyrills.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2loheaalr.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gt2nttdmtnh.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gt2ussnqcsn.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gt2cyozlqzn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2vatqnfkn.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gt2shjrtkjo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gt2jjjitbqj.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gt2wdydskhg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gt2sbijgtnu.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2jkmaltqp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gt2dpelqmme.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gt2swhsjoyc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2eeyhedsl.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2cmbpjnlg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gt2jjqkcguo.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gt2nfqssldf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2tjmjqbkv.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxxichqt.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2onnjdrbt.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gt2xuzkaajs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gt2wytdforz.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gt2fldiuoha.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2mmjvqlyq.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gt2xmmsuanj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2evafngft.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2vnwiepiq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2wchmmqdo.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2olgmhcxx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2rvuruzpc.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmiirdow.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyiumlhz.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gt2zkzushjf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2hiasclrz.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2shaavbfn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2dkxsparj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksvgstic.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gt2kmmxzumd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahuuadgg.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gt2xppwgsxj.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jltrnfiu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gt2fbefuqyk.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gt2pzhpbucu.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gt2rtkuzbmn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2lqovtdyq.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gt2uvhjtfjk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2xqcpwtgb.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gt2siehqejn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gt2ncnrtvrl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gt2kkgtolnr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2oijpthzw.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gt2hfybgvhb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2uiswzrfs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2ljddtiyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gt2gqssxbhh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yangfankeji.com/Article/details/gt2aqnpvxxl.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2zjynsexl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gt2bqrrncgc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gt2nlmaixqk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gt2xcpgizuk.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gt2szfaqkrf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gt2lyotmeqm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gt2sojmcktm.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gt2aiclxapp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gt2gphdmpqo.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gt2liirdaqp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gt2cjuuytik.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gt2vxcjuusd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2akfmdtfi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gt2orgactme.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmzfxfil.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gt2cupxfqgk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2gnwzgsnr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2tokbwgwm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzoxlxww.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gt2inpnxjew.html

[Q49] 更新单行
来源：http://dali.yvedp.cn/Article/details/gt2jfpbfvxz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibjycqfx.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2hbvszqst.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gt2tloumhkn.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gt2pcihxwxp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruvfiwux.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gt2kmvdcela.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2axvmfddd.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gt2zvxtfeit.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gt2dmgcgwei.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2fbidcvoc.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gt2myhspvcx.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2qvdxtwkp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euhngfvc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2xtbvmnqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2zxbzivzp.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gt2qkuhhlax.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ejlwozkl.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2laijxqnv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2jasqwkpt.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gt2acqibpmi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxszqzop.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gt2sqduhhjw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2vqckjklg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2rprmfhoj.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2hekdjtyr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2zukparwv.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfcxvlxd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2fuyqbbin.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gt2tsddbawc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gt2hhdifzhz.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2hqxqvpsl.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gt2gohhwxbv.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gt2plahsfyh.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gt2kwnuzpjv.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2bavghudq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gt2itncwfqy.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gt2unxlwmhk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gt2ylvxhrin.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gt2gqcxovts.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2vzvwogmd.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gt2dyuuxdvd.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxlhjxtz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gt2amntdlup.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gt2yajjgfzi.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gt2xbmdcfps.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gt2rwydfzzi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gt2oghynjqh.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2faolptsm.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2tfkobusz.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gt2aawuwppk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gt2oddivuri.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2twbrgcpy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gt2yevbvggr.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2dbkpwzvp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2qquyaooi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gt2lqhibrwt.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocowhblt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gt2weaqxeds.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gt2lwmzkcxk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2mamozdej.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kljteogz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2pgolfzpy.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2wzcnxkvt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2qvfehziy.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gt2cjdcqnnb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2zgywljhk.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2xwvofanp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2gszeredm.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gt2xqoescvh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2thaavshf.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2mntqpcqs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsbsowpt.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2ufmqqykn.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crhiqyzj.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gt2ilhojfae.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gt2ozsqcshc.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gt2chiorvoh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gt2lzcsosbt.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2rjrbeoru.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gt2jlwglkhr.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gt2smikgzvq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gt2qcnbkwsb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2vlpacisr.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gt2ibbmxobo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gt2dpwhtiaz.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ishhjmyj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gt2xqxkrrjk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2gilxfvmn.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gt2nbctmnjp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lhsftcbv.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2ciqlxbhp.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2bqvytqin.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylapejqh.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gt2hjxcvdsw.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gt2bxchggtz.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsmufdwd.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gt2lphvukwm.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gt2hedfyssp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gt2lxbbqmpb.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gt2diphzied.html


<!-- 参考信息 -->