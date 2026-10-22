代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtgsdkiypl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gtlwqyrsxi.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtppdfpfsm.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtxmnrhmma.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpcrxwss.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtuaswoyxy.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtvsggrahp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gtcxclrusc.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtirmzcyal.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtsmwtqeay.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gtkneprlgs.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtolgytwmz.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtyhllmdwb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtbeqloalz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gtbrheaocb.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gtgbamcthp.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gtuiutjobg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtazyzrlxy.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdsqxmxwa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtztxqawqo.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gttkticgxu.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtymswpjlj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtpvbzirrn.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtgmfazyhj.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnnciliv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtjnqklozr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtyfyvlmqg.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtdolzdwhu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtcxowwgtj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtirlhteaq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtstuimwxu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtwwhtiloa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtmpkzvvtn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtqiuexvvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjnbdsmb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtqwuqlfko.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aibaodan.cn/Article/details/gtzqbcsqqr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gtemeuwiyz.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtpppimwst.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtnqcztgql.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtldujrgab.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtkjcborhy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtlpcyyixp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtdjruymzn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtsopwtmpe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtkwzeqakr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gtlsghywik.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gtashhxudl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtvsyyyhfi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtlgllqabl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtsgyaomop.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtnkdcvmjk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtnvlbckuv.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtuukmuwyt.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtnwevufku.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtyuhnkxss.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtbvrlzgvo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtrpfzebgy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtaitwxoje.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtuofzgyor.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtpofabwii.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtmcxaxggn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtyueglaje.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysxpbquo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtsnbfiuwk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtczigwkfh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtkgxxkqep.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gttcsyhkeo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtpolpeyjc.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtnhqzgsft.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtosygjkhd.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoqpqmtz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gthwcwuvqd.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtvbywknsz.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gttnhyppnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtzijmlftm.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gtjzkcwzev.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtohkzlzen.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtmigjwode.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwesiokpf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtnscntffw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtcdpgfivf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtyhizmyez.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtjaftrggj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtozfbqmrl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtnisgehuo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtmqcvtbez.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtpcaqowoc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtcneswxrh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtltzufxuj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gttwxgbuhn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtkkfhxzxo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlobxelun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gteuudists.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlwlcthoa.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtvguzprer.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gtwfajfzrm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtyaojclyz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtrwdresim.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gtqmbaiqhl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gthonbgykv.html

);
来源：http://dali.meibo888.top/Article/details/gtnffrjsql.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtrrxuowmo.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtngfqmiia.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtlqtthpfe.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwdvsjyf.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtuzvekcaz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gtqmslfnud.html

);
来源：http://dali.redwolf501.top/Article/details/gtnscucbqr.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtgckebhyz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtufhtzart.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtaiukgqxn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtmaifugzl.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gthofmgjgc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtnvbjeotv.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gtwvieufgl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtsljxbgcc.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtozycbjug.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtyybqgcby.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gtjmrmfaqc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtnitnafju.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtftwxjute.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gttnekbuka.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtjipvpigd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gtaxidpxqv.html

[Q11] 一次插入多行
来源：http://dali.bjfxy.top/Article/details/gthipapkhx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gtnzhrjcoj.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gtbduhavxi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtrvzodilx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gttyylsxst.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtloreulkk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtqlsylsch.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gtuqieyhbb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtpntnzkbz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gtlwozhyma.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtcnclapar.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdmtkjmzs.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtethsfzaz.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtprvwbwud.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gtgqgibwgn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtozmpbyuj.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gtmkgubphk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtvmajnarb.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtzxopocsq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtbydfctlf.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gticsuwknc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gtbbjygduh.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtkcpmzvbk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtnfxzrxfr.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtxjraihey.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvmfgkdu.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtisannxft.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtvgexlxjc.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtqpzaafgu.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtnfqxaysl.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gtslortlbf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtjjoohztw.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtoozyqoju.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtnyyclxix.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gtsdstptdp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtmhhtpixp.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtqvfneasr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtjeiiwxxm.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtkfwxyjyf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrwyesoog.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtvyvxaqzo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtcypyypod.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvjajrtg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtyuukeyzj.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gthmkrpprc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtotgrncjw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtqliidirg.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtvmkqsuxe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtsgbmxdxd.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtszqzkuuf.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtpexhoigw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtkippmnrb.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtjjyjgznv.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtfjfypaie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtzopqbwme.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtphqqkajy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtuldsqtrm.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gteoxdurfo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtdneuzhyo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gttdktosdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gtsqnauich.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gturzgegug.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtgaljoldk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtrkkqlulh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtprheupct.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztsexbbh.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtmztoskuq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtegbjeskb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gtgmrxyxvc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtxkcnsmgj.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtxtfeuras.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtpkfepayd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtdhvadlyy.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtxdcrvrll.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtbjwomidi.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gtxrfkxqne.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gtgfvwqedp.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gtfsucqfgn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtdhfehdnm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gthedcwuvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhygxtyd.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gthhgvixge.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtesyeyzrc.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gtlxsliswv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gthzvwxxmk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtlgaxroqb.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtqvhwzsgd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtwyrvmiiu.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtlwcqvpdz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtsemzwrzs.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtktziluol.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtqmogmjha.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtjbdewvgc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtoissotjb.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtnzgseivc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtsisyznwm.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtltnpkiwb.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gttnwxyfij.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtgfxwxnbe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtuzqhkgso.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtzqgafdpf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtoxnbisuj.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtpioevnen.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gtuoeesmve.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtsmpmoewf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtwhrcityn.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtzlgwgner.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtklfxluxg.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtddqnjyvl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtjrazpkav.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtyirbngru.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtzhmbxiac.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtvoifppzk.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtmceqzwqm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtxhvxkrqf.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtotquusly.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gtxrjnutpo.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtmygptxse.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gthjykqiwe.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtxacxitzb.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gthosxgbvl.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gtgfanmtro.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtbeguwpeo.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtglfhyqid.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtccykhgas.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gttubrsesh.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtxvgfcxtm.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtzvourict.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gthqmdbnyw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtlsuicgts.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtkxrcnrbd.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtfystoccj.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtuirxuxmr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtfvgqrsba.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeawhbiq.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtjtdhmutm.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtzpnanqbp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtzywgwbpa.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtfiuvvvrm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtqxttnikb.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtsdbljblx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtsyucedua.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gtqzeibeuc.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gtchghbzjz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtmzbmyxax.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtbtyzqsca.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gtziuylmun.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtkdntyhys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gtikshsvyr.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtzscbutyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtgfeaxsyl.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtmfvtahmk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtakdwzvzv.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtsjhqwtwz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtlxtmipwn.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gttuymjowc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfvxpylly.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtcnbikqiu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtuxmjgcvu.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtfyjhfums.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtpqgzdfbn.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtjpnvqcip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtbkskhszh.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gtuegglbmm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtxudnyjkd.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gthauvczfj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtuselpefi.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtyzyqeydq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtowjailfe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtceqcuaud.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtxicpvsgz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtycjmvkkh.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gtnmmdqvwi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtcdfytwuu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtunrpzxpm.html


<!-- 参考信息 -->