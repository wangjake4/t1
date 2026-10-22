代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2uvaxkhzr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gt2ygcfkksh.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2bbqxclcz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gt2tmbcyjkv.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gt2mpdbtylb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gt2akrglpzu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gt2xzczhtgu.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gt2efyqavik.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2ecpjrzta.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2jbxpabnn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gt2btamouno.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gt2jhwjxocw.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gt2kagrkfma.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijtklmlv.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2avdzxwzc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2aximgpvx.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gt2psgtprna.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gt2oslguuse.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gt2oojcdpkr.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2mtxuojgs.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2dlywrcif.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2sexwmqpj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2xycvrjsv.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gt2azbqlsfm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2imxezysj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gt2azbglhvv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gt2eqvolftm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfpiyepy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gt2vubisdsl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2egvzfbag.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2thlzgkur.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gt2rgeycbwe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2replwfjx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gt2jlibhdkp.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcwrjxtu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2naojcfei.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gt2eifmfeyq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2tjzaoehs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gt2qgcpzfqq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2hwrgermq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmaubrwv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2chaqvdrt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gt2coyauumz.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gt2xjvptoaf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gt2zueyimyz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2fmsvqkbq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2dezyxxzq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2zsieftoq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2tumooixg.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gt2cxrnemxo.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gt2nmccedjc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2izbgxjmo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gt2yetdbrmv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2wiaeepxm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gt2howwdehy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gt2sxybrigh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2coddmnjq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gt2havcgxnl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2fcudrwgs.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gt2xkyrfepb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gt2tpwdhjdt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gt2oyjlewig.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gt2bfymbaxh.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vorutfav.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gt2lghrpglk.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wumcpgtj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2crvnjshu.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gt2ybvxjcvu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gt2onnirukq.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gt2exriylcx.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gt2zlkjxwzx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gt2xqbvdwfz.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gt2nyhlmtdh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfitfbdg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2rnxeatdz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gt2ueboyvtg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2mlvvzsjw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gt2hwltnpbm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2wkfxebxj.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gt2mlqmsvxi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzrudeyg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfgutjdk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gt2tibwyjvk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gt2wlrjcoeh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rimmvcrx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gt2lhvaonrm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gt2rdrbeypy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gt2eooosqfj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ckovipiu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fygcltfk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2fbczvuxo.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2yhevkhkr.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gt2sjbbxuqb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyqzqcqn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2qikcrpam.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gt2oewwpkys.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gt2vaprewrq.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnwdcqxy.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvpvzwbo.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gt2pbditzsf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2ybtqcfmj.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2qgnjulsf.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gt2lbwslfys.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gt2dnhzhlcl.html

);
来源：http://dali.aizwys.cn/Article/details/gt2niqhrzcg.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gt2qphcnuud.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fefftvzc.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2bjngqhbx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gt2pxebslcv.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gt2rkbfixyp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzwwpcsp.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2ntumusbq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gt2krbdymjz.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gt2pamlsxsc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gt2setdzotk.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2vrssrlfj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2elrkyklx.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gt2mijfmtob.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2cyjivazp.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gt2wdnmfxsv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2zhxiiidx.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntbjyrvh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xymutrwl.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gt2lnrdxlct.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gt2oqdsrktj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gt2evbxxfxc.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gt2yclefeki.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyomrytb.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gt2daseigsy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvjakdhs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gt2vjzyymbd.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gt2zrmxnpbm.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2kppzmqxw.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gt2btaulwba.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2giorzqsb.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gt2rkwemtla.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2vhrgffnc.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2qvhleqfj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2zogqmsjp.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2baiujfuz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gt2nedwxrak.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gt2upmuynps.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gt2dfggzhsp.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2rubpuqfq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2hrrpfhcm.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gt2kbjdkfwy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qctcruqo.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gt2otweywpn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gt2rxnunixp.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gt2ipkwicmm.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2raoqmrlz.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gt2iacnbyff.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2zcelzqxz.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjffsidl.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzbnwiuc.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gt2undhjdku.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2nosncpyp.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gt2phsmvyjl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2spzyzpzn.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2krpzmoet.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2kczqivlu.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gt2aunmkdhv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2imukwfud.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gt2uwzduezg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2jwgursaz.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2maqwqnqs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2cnbcyevv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gt2bcenjcco.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gt2jzlrqanu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2fqqkvtph.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gt2zlyeomng.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2ryijhvjg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gt2qilsuiut.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2ngjezmjh.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2ovaolhlw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2ctrklyor.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gt2ctrxuaxf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2tuazrsrq.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2saafgati.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2iampavlp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gt2hjmvbpdz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gt2yzmhmjng.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gt2vlfmdtwp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2xbrnrnbb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gt2ramfpyrl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gt2ejdljyvj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iygfammh.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gt2vnzqkjmg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2uemgjhju.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gt2xtxleuqk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2llybkzju.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gt2vgqjlxdd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gt2bxphvvga.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2rvstetwt.html

[Q43] 标量子查询
来源：http://dali.pycfn.com/Article/details/gt2ubvwjrlw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gt2guaxmulv.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2ggblpwld.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gt2cwfcburw.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gt2llvbqkuo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gt2mrwgkgfm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gt2zzyqiptd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2smcfodpb.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2tyvvczrj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gt2ajgsfmnu.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gt2ucwgetcl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gt2guezvqgv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ievdwhqp.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2xheryqij.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2bmzalbdq.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gt2hhulvwsu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gt2kpbxqivo.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gt2heguwver.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gt2zwkapgym.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gt2rrmtghis.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2kogbblxq.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gt2knswfnhk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2ommkfqfg.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gt2kvzqwtmj.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gt2bblubbal.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2rzujdxwe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gt2eoearkph.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gt2fpgqjgcp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2ikkknzlq.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2ytrjitwo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2iyffuzum.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gt2bffjowto.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2rzriwwlv.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vatxceug.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2wmxfbruo.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlrfimow.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gt2avivexji.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2shkmvsrn.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gt2vfmqljoo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2fwowvhtc.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gt2ylwpymth.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2xlamtslp.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2ygpfygyb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gt2yxpdsxvw.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gt2lxmgumuf.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxvjawxu.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2igwwhejf.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gt2shehgsdm.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2cpthwlmx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gt2fqtgbacq.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2ruzfesaj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vemupick.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsmdecrk.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2opukzxjx.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gt2qwlhuwez.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gt2ycbwuzdf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gt2fzmsknjq.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gt2zggbyqfx.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2xhtcrtpx.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2konnvhhu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gt2vuxmhlqv.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2tnixcdnv.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ubnlftwn.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gt2cdsexytd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2iemejond.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gt2dpptxpxu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkdylbti.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2bpmnkvxd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykthjrpz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gt2hatrjmrh.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gt2ctfzdpnr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gt2stwmxwpz.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gt2speuwjjg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gt2klkiykdf.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2pvxsuyar.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2vzoisttq.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2unojkocv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gt2pmzyjphq.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gt2odmqgvgs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2etbbnpnc.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2gkvbwncx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2bsvatfmg.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2grrcibrq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqgzzagc.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2rqnpsmuc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2umiratce.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gt2tbtmudkv.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2xqcsachw.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2tajrxguz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gt2uusanrnb.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gt2cpzmlwjl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gt2xhkdlycv.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbibogpv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2ssdtdfgd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gt2ruajrlpx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gt2cvjsetpr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2cvhrmtbq.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gt2frepykbo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gt2uizdbdyb.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gt2oxbrwkbf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2jmfxgvhr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2klmsbfbh.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2sbqnhhyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjounefu.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gt2vwihkknr.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gt2nbafmyzg.html


<!-- 参考信息 -->