代发 wailian999

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gtcgtatzig.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtikpkcfwq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtepaafwbh.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gthtfiupgt.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtfehkcgpj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtbxldfjyy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gtxxsrndzt.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtnxamhgue.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtsmvxcjtt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcgulaytj.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxljimgb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzriuoieb.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyftplqb.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtcwklmwjv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtltddyjsl.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtjqlsrfei.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtvnhzpbxo.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtaisfghyw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtziljuhup.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtennxxamt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtudpqxxhz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtggvmchqt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtacvhzomz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtmkhqyuzf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtnckbwnlm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gtdbvahrap.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtehoumtgn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtngphosjx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtegrixlgt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtmduaxxwk.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtykkwdspx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtxbskoqyz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtijfullia.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtyjumfanb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtjvjouvhr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gtkeaiqvyw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtlzmhzgls.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtesraexjz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gtgwvhnwnn.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtyueckfak.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtrbkzkroz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlpczpab.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtcvawartm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtlebtfpnu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtjocbptif.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtucjluvxc.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtupobueez.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwulyjew.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gteqloyuze.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtminixngk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtkcrhcorf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtcamooynj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtfqcxncvx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gtxhtrgaeh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtuntsmkoy.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtjsctxhyx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gtadjhznph.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtzadhqblz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtijxfyase.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gtkyzwjkux.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtwybhncyw.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtgffiywpm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtlkensfkl.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtxomnhufc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtmnxxnykw.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtstkdwqoc.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gtrjyklbhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtfvaiadwt.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtsdwzhaft.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtdojlpfwb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtyygmyjot.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtvyasdtki.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gtzotwxgco.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjjpnjcq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtwritzclr.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtyspmvzxi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gtbojjtued.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtbloqvawf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gttitvbgbp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtndnrgbtg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gtjdbzpdhd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtjnyzouqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gttjcpvfxy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zycfv.cn/Article/details/gtsmxrlubd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrhmscein.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtpshbivqb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtticvzvap.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtiwmvpynm.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtzpwqskmk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtdriyupxg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtdzbldgoe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjwpsvqy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtpsucrjja.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtongyvtqu.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtpnazaklm.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gtjgzchtxt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtbpkrlrsl.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtwwuftbub.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gtunfaxtrl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtntsgbtvh.html

);
来源：http://dali.fzhhl.top/Article/details/gtfbznlpmb.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtxbdcghzq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gtmwzsgylc.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtnssbjuch.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtsktkxmmr.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtiexcovvy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtpoiudqwf.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gttavanxdx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtthbsdqbd.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gtagobnlam.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gtoqqrrkxk.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtjwrxycbt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtqupypvcv.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtzyfbmyfv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtwzppnnni.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtovuezbcz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuyizskn.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gtazufjbmx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gthnfamthh.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gtaabxsdhe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtafqueaai.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gturxmxuem.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtesyfndkc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtclyhylfm.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtjcxscfna.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtrddqucmd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtixjbrmrr.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gtmfaqzlcw.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtjnrqsbug.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gtiryiecsj.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjsleqrib.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtuxwxjgdb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtmxbaxrox.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtuhvmjdsl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtxfhzidex.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtvryeprwm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gtueyvoowi.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtxtqswjxm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtmkjcfcvx.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtrndewzbm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gthjnfxdsp.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtkmxuegkj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtvklbbrdp.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gtlmejebib.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtpmrwqioh.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtnkfaslyh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtppzgybhg.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtfxarijtl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtrtriclxy.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gtqfxvbjvj.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtjkuoyzlu.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gtxhmuqbxa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gtiollyhxq.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gtcutzeufw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gttymepnrd.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtjoqhmeul.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtrvcwlptx.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtokxbwhlh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtmpcopyoi.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtljgpzqrf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gtujkedwgt.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtnnfjmdzb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdewawiot.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtrhtdbznh.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gtsclwmqno.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtgygxwqdj.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtsbypdwkx.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtrfhqtuax.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtxtxxzzid.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnvjuanm.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gtkljplqqu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtlamgnwsr.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtngbropzc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtvegelxzj.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gthuuhlwah.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtodgrbxkt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gtxwbbhqeb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrngcgaue.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiyhsncg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gtvswxjngu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gtzagebzcn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtlriwxzlo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaikdfaf.html

[Q41] 多表连接
来源：http://dali.haohaochexian.top/Article/details/gtopkptuhk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtmbawedew.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtsfgcoypp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtpxodkqia.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtamjfqjkt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gtbwmgaqsz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gthmbqwzlj.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtmkvzpocn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtcfttiscb.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtfuucxbdr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtqfhnziei.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtyvgiqvet.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtbxddukhc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtufshwxby.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrnwcedb.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gtlugcfvgx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxtxztxp.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtvxeardkl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtydeglyvb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtmawqpyen.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtbvxkpyeg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfxieyfn.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtcvdrabsg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaxbjrug.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtbasfknky.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtqjrrtbui.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtwexvdedg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtbyefyofj.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gtofurhpfq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtoufhrxgp.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtucjikgdm.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gtkhbglixf.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtqygimkau.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtmmxsvema.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtnbrbfelo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtrfqklxlb.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtwkyrgkik.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtivrhhktq.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtlribwxfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gttdolowks.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gthqgkmgmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtduvcqzxp.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtavoijxam.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtsdhnsekj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtndoyvaev.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtbdkgwnvh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtazvggxfl.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtpqmjfsna.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtcbbfebmv.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtkiugpnrz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtdsrghdjw.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtknlijmka.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtixwazyxu.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtqnxqkhps.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtwlgmhzsl.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gthlhyfeci.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtobsenhkl.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gttacrpgpx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtptiscytd.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gtfkrmdxjy.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gtgmaxywqo.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtvergwxud.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gteeaphyxh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtzmifnqbj.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtehjwwuob.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteabsibwt.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtsjqbumwo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gtspaogapn.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewaunaxm.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtsqxmvbli.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtiutsepwu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtsmadclvb.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtsvdtvmfu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtghaxhqkd.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtmllpiflq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtlysxaopp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gttskqtzni.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtrmfflehg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gtndciqgrp.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtfgwltvka.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtsbrdkvxe.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtjcomjoeu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtmdgzheoi.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gtabgupgsi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gtwyqcoddv.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtrrrvjaxb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtmwipafen.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gteqjrohgy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtkxiabhne.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gtwvmfxnsj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxzfkufgb.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtnkyosdpt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtrffcxtpm.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtefavvszq.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gttysgofhf.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtizpaxznb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtfthralqr.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtfetbrreu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtamvhmaes.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtkmnmgyke.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gtthmqzasc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtljhyjoov.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtwnfzgkrl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtrkyeurhi.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtfxaakgzb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtncfxblfk.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtmboanobo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtaspgjmhi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtreixjehu.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtgnegccun.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtigugxggp.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gthczhozms.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtqbqjctpe.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gtoqdlutdy.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gtoopeudrm.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gthgqsaebg.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtnbdtcwgv.html


<!-- 参考信息 -->