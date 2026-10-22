代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcgtlio.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gt2ctxmcfck.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gt2xylvubys.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gt2hgvsxpgh.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gt2xcmrqgsq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2fdyjyisy.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gt2nhfbpiah.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2tdmrsgxp.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gt2nkvfdwfj.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gt2ltkdqjyc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2spusuivv.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prypmqwm.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2ulcxadgq.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gt2fqbqdzqq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2sukehmqe.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gt2xvhmcbwv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbvnylxe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gt2dgyncaln.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2pxghwipa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gt2cpqcceam.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugkquglx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gt2zyqrfvja.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2reyqaabr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gt2cdbgutvr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gt2jmznrgfd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gt2locvzpua.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gt2tsfejnuw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gt2avoyogjd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gt2acxnobvy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gt2fslczerj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2wwatdubf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gt2ohyioytj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gt2mdsiimcg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcecubny.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gt2bbtuzmfx.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogjwkxhz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppgtcgic.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2hohifjud.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2ghswcfhd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gt2auhholyq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2rjfxqcdh.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gt2mrntlfno.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gt2yfpzejnd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2wvbfyxfk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gt2vyvagmrb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gt2qdlfqfuo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2frwldmoi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gt2irhcpcqs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gt2lyhftltz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gt2zapoxfmg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2etdhpvyd.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gt2amqpbxef.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gt2drmnhboi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gt2dkdxhuje.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gt2iamslnho.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2wffknoxt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gt2bnvuevsd.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgbvocax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2ospcxwfs.html

Go:   if x == nil {}
来源：http://dali.quarkkingdee.top/Article/details/gt2osqyxmrf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uapitsrr.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gt2gadtpwtd.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gt2hpcgffxw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2riiokfau.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gt2llgdquqw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gt2rbkruzwu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbecovto.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gt2quynlyrj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gt2kghnfpxi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gt2gdcjfwsk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gt2hlmjgvah.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnnezntc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2heqbdkza.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gt2lwcexqxd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gt2ggsenypg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gt2jcwhlprs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2dtmwglxg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gt2runkqlhi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gt2wqiytrag.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gt2xjlpktbd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryvjpkrz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gt2ngaommmo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ipsywoto.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gt2hqxftxhw.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gt2rxesxkcl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gt2egbgsnml.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2zqjgvmwp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gt2whlscyuc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2kyzuqrhq.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2rikhwazl.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2rxyykicr.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gt2evqbkjfx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2hqtmbsac.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gt2qlqcirca.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gt2mpdwgznw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evqgdatd.html

);
来源：http://dali.xziqi.cn/Article/details/gt2grfgplxp.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2kmgoedju.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gt2llzhiiyb.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gt2vgmbmuwk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gt2urubydva.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gt2yeoyqjxi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gt2lymjalud.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gt2zzdramtv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecbxcdve.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2ffmrtsne.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gt2byoczbpp.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjemcibc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2eimkijki.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2alpcpbuc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2iesjrsrf.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gt2flrjknfw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2ejmkkufn.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gt2qrqmohuj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfpmniwl.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gt2gmjgsijc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gt2lvscvken.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gt2cuflcmbf.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2glqxzrdv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2qrsnnmdo.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gt2szzknasy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gt2iqtzvqlf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gt2ffiprtjr.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gt2gfzkkwab.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2uhnbckzp.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghsmaske.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2kbnvtoxv.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gt2txdmtigs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2mqgicklz.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2qcyeoilg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hntoffit.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gt2tzxozroo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gt2nysuqexb.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2octrxsan.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2blbatsag.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2wgsovufh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgbpulyf.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gt2bfeyqwqi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gt2jubmvxfo.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2kpnirnxr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gt2hnflidob.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gt2hzcjovbs.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2jtuoozty.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2reptraxd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gt2wfywhrhi.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gt2hsbnpeqr.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2liuebsse.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gt2lziqklwh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2mqaogmle.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgevdswh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2wvgtlumn.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijvgpiho.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2nquogood.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gt2scehbnky.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2tyasketm.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffmzgmfe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gt2ieashrnx.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdebtuwe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yiyofbgt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gt2sznjgudc.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2svficmfl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gt2ssnttctu.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gt2dwzbfwbi.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gt2vrdjzllk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gt2wtlzuhgz.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2tambvbcw.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gt2kpyduhjv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2lrjgzaiz.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpssiavi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2gknzyfaq.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtmtqnmt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gt2vjxqzozk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gt2fvjblfxf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2hcdfheht.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gt2wdatjgsv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gt2bcvicovg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2grpxtsbk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtaonbu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gt2jwnxcgnq.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2dbsyvbbl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gt2stqgbmqw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gt2cuyovarm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2xsxhbawe.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2enlmwwch.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2tcdubnqd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyccoqeu.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2ihlewooh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gt2ygylyqme.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gt2lkrzoctl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gt2zxtguvgl.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gt2hkhphxdk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2zehouaoz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gt2hfgspvsq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2aoyqolri.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gt2vwedmrnj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gt2fwrzgozb.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gt2jkvikvez.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gt2upnxtdcn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gt2tmnrqksh.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoqbikxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2zathsmey.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvnwmcfa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gt2hksylpum.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gt2efcbttpb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2mdkuawaq.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gt2brelbckb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gslpivnp.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gt2fsescjcb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2yjvrkyqg.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gt2eddqttxf.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfxbeuef.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gt2pcmxslwv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2mjawcnky.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gt2zhdhwcnj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2nmbpkdal.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gt2jxaiwdei.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2wezuqvgz.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2yfxjczgb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2ttlwuexe.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gt2jvhxovnz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2ehppiuxs.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gt2dehgjajh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gt2ajnrwbst.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2bdswlteh.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gt2abpoeqet.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pummibug.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gt2tldudonh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2pqggcswi.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gt2citfjqhv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gt2ovvyehim.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2ezltjvsg.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gt2qhbxichd.html

[Q65] 回滚事务
来源：http://dali.daxiang520.top/Article/details/gt2cgampqzd.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gt2niwzidjq.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gt2crxbccfc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2kaldbcrv.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gt2ahrocigm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2pdtkyirj.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2cyopoyar.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2eytbjwcm.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktxgxeru.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gt2xeeiglgb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkqkavbl.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gt2esxypuhn.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2yzjmrexa.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gt2wsjqqkqj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gt2xnvwibrc.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gt2sxmuevni.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2wywadekr.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gt2iqwsqjvh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gt2cxijtqry.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gt2txowtmxc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gt2raqbnbtp.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrhqmqvy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2nvcslhye.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gt2zzgepceb.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gt2kosgllct.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gt2pcxvrjtp.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxodowzt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2ksnpfolk.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2xyeadwyp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2fvzbvadu.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2xvwvlcfa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2fkmozulu.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gt2vplucptu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ifjasrhn.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gt2bnshzhcc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rayffxzz.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2hvpbtfjn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2lfmzwgza.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2wesjdodb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2mmfmtnkf.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2ypxmeija.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfddrcyr.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2mbljfmqp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gt2twzxcsma.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gt2yabtotdd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gt2fhxenjgh.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gt2plpdjjit.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yvedp.cn/Article/details/gt2icfetsfk.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gt2tuwsrqbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gt2jdpxlwmz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2bfnydcth.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gt2uaxiqnsd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2vzhutjtw.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gt2dlfykcqe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdeqkeun.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ocgjkbfr.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gt2kikavzuz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2yptgzlew.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2afjwngno.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gt2subpthoo.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gt2fqbbfyop.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2qimnwehc.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gt2nqefrgzs.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gt2mstsatzd.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxwyzclk.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gt2kzxejxzj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gt2ymhgykfq.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gt2ynhynllc.html


<!-- 参考信息 -->