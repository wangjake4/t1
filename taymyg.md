代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gteoxydtrf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gthcruwwvi.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotpgvlbi.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtebibrfbu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtaxyutlny.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtowvorvpj.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtuxrhnacj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gtuyetdfmm.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtsheadgyh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtmitmfogx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtrxdfqbzt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gthxhktwcf.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtyuomrttl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtfyzghzeo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtqembjhsu.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtvxekuctv.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtbynltcsu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrmhvzehm.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtpndfjtsu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqwdurcxd.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtnkslupao.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtvcrbffhc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtgalgbgve.html

JS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtbdfsyrhd.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtubihvlmp.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtbcaxuhoh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtvflqyjmh.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtolhitqix.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtvjpbrxng.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gttpfgcnvn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gtvjqnmzjm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtjfgvrgma.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtgtcqkakl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gtpejirjec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtccewgcte.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtwbxtfnnb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtddzxmpkw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gttkodwmax.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtvikkllxo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtylxqdsqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtfchocfuj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtasdykffc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobdirsne.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtkjpayhkg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtukixppno.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtzpgltxid.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gtdrzuxwot.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gtfelazvch.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtabdzcfcq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtdyjfcnwj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtubzcgywz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtopscolkd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtufadpgvl.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtsmxwgcyu.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtqyqqbzei.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtrddugduc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtylkoebqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gtqooxbecr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gtkcfkmfrg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtowerlluj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtkqklohro.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngysqqwd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gtyquaoppv.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtkricxmmb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtvxsbuypf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjytfdnj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtiapytdvb.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtquhuuuec.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtioljgadn.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtjlacbpau.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqlvlajwj.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gthudtrpzz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtfcdangbg.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtovaoweru.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gtujwemfid.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gtkpdxlxyg.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtjfxajvyc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtultasbfk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtmtptpxfs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtxxmphlip.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtdnmjwhmv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtyefiokey.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cdnleiting.top/Article/details/gtbmuvthvo.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtioabrinq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvgiasaa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gtjwaceuzg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gtvndcdpcl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtxuqhnmyn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gtrapnrkmw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gtamruqfjn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtzvgxszrb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtnwmuehui.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcjkdakmd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gtfhljcvlu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrifzdrl.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gttnmygvxt.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtlzzrntoz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtvcdazgdd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gteicxnsyw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtcepxpjkh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtgqdijmrz.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqninjtk.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtjwnxfssn.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtmiwvcnct.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtbfdycqgn.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtwpgwvezv.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtjjkxhxdd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gteqiacxmp.html

);
来源：http://dali.redwolf501.top/Article/details/gtwgmzxmxu.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtdntdhjin.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gteibiapgm.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttamkcay.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtgttophkv.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtnqanpsuz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yongpay.top/Article/details/gtbmggiscl.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtizukubnu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtqjljmgqj.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtohoswlzc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gtnjkxhjhw.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gtocbbpbhr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtgsakfyhn.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gttmapkeds.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtzebxiqdh.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gtqaxhbuxa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtsxiipaxv.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gtmjuqegco.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gtrdwggewn.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtojpbotdg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtuisvapld.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtwnqozgqf.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtmfwksvrx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtaivtgrtr.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtkwivxlvi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gtuhbfilfz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtwjvmuazz.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gtgxogswid.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gteajdqjlq.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtuwkzziqy.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtfzewtgeg.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gtdphfeovy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gtihkltgeq.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtasmgphvp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gttqxvcbhh.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtxoclogwk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtqbkxngpm.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtmxpvaryg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtycrcrcqi.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtvzbmzwbt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtdldsjxmp.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtphwbouoh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtuorgvdiw.html

[Q23] 分页
来源：http://dali.zhoulong.xyz/Article/details/gtfknfsuij.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmbpbyor.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtdhfnmrug.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtbgyxhvew.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtnkzjobih.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtmoyxumit.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtylrytoyc.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvfojffps.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtnjutzpki.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtmgawidpy.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtfqfecwxj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlknjwuka.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gtpamotifo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gturosouam.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtlkvtkkbb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gthfunyujq.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gtsueepydj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtqcnqhhzq.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtkmjetdhk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtnmkcozax.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtbtfalfqh.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtxlgcpncn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gtujvdpbdz.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtpibrtmlj.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsoedlmk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtnzbcdnto.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtdiypawgz.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gtxgbxhtak.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtvilgxyle.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtxfwgasaq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtqdfvlkrn.html

[Q37] 右连接
来源：http://dali.jlsjyb.cn/Article/details/gtkajxiatn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtfikdfsnn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtocrwhbic.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtfktwgars.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtrvynfhcr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtyshspzcm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtqwimtctd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtfpakmr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtrevnoaux.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtuypejuew.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtfjtcybyt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtijiuwtih.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtelacjfyd.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gttioopjqb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtgofuxaix.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtmbjsstod.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtkaycbjcv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtpmiaoysr.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtzbhyipee.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gttbfdeymu.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtsgnayorn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtyvkvoxle.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtcsofqsxk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtggnlfrct.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtujhczaah.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtezjtuyfp.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtydvsnuin.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gthescxrel.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gthpfafoik.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtgbslstii.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtcvhobjxt.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtnvkzklsl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtfxryrhez.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gtiettudjj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtrmwpjrpk.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkrpjsio.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtbhcejgql.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtuewjzevx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gttxonirfj.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gthgkvavhc.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtkllnofoh.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtnbydlxvc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtaadvfbme.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gtxtwuxwia.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtgxmkxccg.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtqlgotpco.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtmohxzowd.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gtzoadkahq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtglijseud.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtkahiyiza.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtfaupvart.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gteidwbemy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtphnwyyxb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtdypislby.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtmhmxsowi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtidtlbmdp.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtsddwnzet.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtwytowrss.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtddvjjibz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gthzqvrjqk.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtxifemujw.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gtcnpsrteq.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtotgwleci.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gtoswkhqqj.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtsfkqqwae.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gthihtvpcz.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtdgeoegwo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtrnnluzlb.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtalhohoff.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtrznrruiw.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtsgfjquea.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtkoomweyg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtvkrghrwq.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtncnvqqcc.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gthicscapf.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtogsfybkm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gtwdxtzjwg.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtdafxttlj.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtsgqpkegn.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtagmaojeb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtauzwstlc.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtirtdzumg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gttqlcftny.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtfhkrcjeg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtayrdpoeh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtzhxxyoec.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtejrrllzf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtpspziwvr.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtsghvzypq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtcoucypga.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtxklmgarh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gtjeolhhfz.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gtfmltnjyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtpptrzpyq.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtnmxyujyh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gticwcsjhp.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtjieeekey.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtikcpqvlk.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gturrlofjm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtlfnzrptc.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtdfnwjlyx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtmyooahhx.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoxaqiok.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gttbxqgpxd.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtgsrlqehd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gtshniapus.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtnsbcgwhd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtcypdazmd.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gthodsrwgw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtldrdiybr.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtmllodrnb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gteivdmbpd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqvodkhgf.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gtxyvsfkqy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtrjgrzwmw.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gthuhrzyes.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtkejrkzbv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgbnykvpc.html


<!-- 参考信息 -->