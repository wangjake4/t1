代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtzjrwoief.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtuntrlcsl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gtbwilazod.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtmbmtozfw.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtxquqvafp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gthehaeuzw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtfrcxrypy.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gtuarhnhoz.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtzbstmafa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gticppxufa.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxygtafqq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfhwqpcsb.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtfsyszfdr.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gtnhjhrjvz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gteslcvvnd.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefwglumy.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtnmjvaqot.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtflecjihf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtqoksdtol.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gtkyvsditu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtsfehhyiy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomarxdkm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gteddlnmze.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtfqtrhufy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtrwkfjxlp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtptjjvdkz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtfukiqlzz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtivkotfld.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gthvczkhfa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gtwbxqzurf.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gtcnnwudtg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gttmvgaypp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gtoybbjntq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtifshedbx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuynipsz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtvsvrhxum.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gtsnyngrsm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtjmzljzvy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtrdzfgvqh.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtpfgsqvpw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gtohuvkynt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtehojuxoh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtluhnumcs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtgdjpywci.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtknlvlbqq.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtbntaiu.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtfecfooan.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuexsakd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtkpypcgzd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtssdzspmc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtzhgtakmd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtfpzjwant.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtzkmowxea.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gttghfpuza.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtolfqnobb.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtydpihrbe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtealwzjru.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtsknkqmnv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqswohci.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtsxanpkdz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gtnqclcleu.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtkxpoydhh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtqzxeboyi.html

Go:   if x == nil {}
来源：http://dali.xuetiantiany.cn/Article/details/gtowhjwbtu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gtazdlppnl.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtnzlgtpwl.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtmpkjtopj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtvzmstxbe.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtgpmmcebo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtfsilqinb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtxfqkqjko.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gthhrmsbuh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtwgwrmtio.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gtpyzqjvzg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtiidpmtnj.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtpthdttoe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtgfmxawal.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtbkxmypjc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtrbssydyo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtiitiazfv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehjfzrmc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtmzghwzlf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftuejogq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtxoiuaaxz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsuaxrivp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gtfzplfynk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrxdyeuhy.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtaskedtxb.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtgrpkqxkb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtcalfporh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtrqomrzvm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gteqiohvgq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtuwqaweyk.html

);
来源：http://dali.meibo888.top/Article/details/gtgoczxslt.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtfwnvsjbx.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtclsfwveq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtsfuntvda.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuwavqub.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtoheyhjed.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gtfvghkyzy.html

);
来源：http://dali.hammf.cn/Article/details/gtqjgojwvg.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtcbgxypyl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtfznuaskr.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtcjdrnltv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtucugxumt.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtnhcpbqig.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtnqdxmzvl.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzsofsba.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmtzheup.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtnvvnmivh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtfoywbyye.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtrsefwyjy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtbgephzqz.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtccouhyqr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtoqsvhneu.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtjhbepxew.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gttjkgpzgn.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtqidnoblx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtghcffeda.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gtjmfejyyb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtrszuajvf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtprrkxwcj.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gtbkbaikfk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gtpeaxlhkg.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtlldkqmfr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtsogconmx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtbvsafzkl.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtdkwrzkvg.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtwgbuqrwn.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gthtfwlngd.html

SELECT id, name FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtuywncgsk.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gtaboijuji.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtaqkktmyy.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtffedtvjp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtaiqcfvas.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtizqrhamk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtpgjqsomg.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagkzbyea.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtkmornwhf.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtfbgzxcvv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtclzjqtqj.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtvtdurzpi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrnasydl.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxjsahiu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtelkpkzob.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtoapzahgf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrfxazhw.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtskbbxnug.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtmeumtccn.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gtqjhjviiq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtwwhhvrnk.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtesrljfgf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gtrqtjdcmt.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gturknlpkv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtcaeltlfk.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtkqisyfnw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gtlzlkpofd.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtajfydywt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtsrakbsux.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtansxxmof.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtxazcufod.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtjvvohyta.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtqnkjrlao.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtydnshssr.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtxqhhhnxr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtduycsacn.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtksitgwqd.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtgqgtigfr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtdwiewxwa.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtfyfxubus.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gtfwezhyzi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gteztheeky.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtjdzeddhu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtgugqdgvn.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtplrochhw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtbyejeujl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtatcejguk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtumfraiyu.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gticbqqazk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtgmsuswel.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtloaxrtug.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjqkoaol.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtpufobfsc.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtczejapjt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtfynxmtts.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtcbzbjodv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtnhlzrisu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gtnomshejk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gtoxeimwgq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtkaxfipxc.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtzregbjrd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtpmalojio.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtncmixrop.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gttqbnqigy.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gtaxlfdcge.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtqmdykvan.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtaebrmavc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtjmzmjzsq.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gtmovdiizx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtrrevaher.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtsxnzpset.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtnbjhdmap.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtkhgxmvbc.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtkeyqmaze.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtoripqtty.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtjoiogmxq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtgmmhrnqq.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtydwhfmwe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gthwwptbyp.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtwnsqwehy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtojldunqk.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtmpjbelyp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacwlfqdm.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gtzqguxvfo.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtwsnaecwe.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtjkwzzubi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtwhalolry.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtwmnfeevv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtvawwnbtv.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gtszirpmga.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtwpvkvyot.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtkajpaxdt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtxbywpubi.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gtfptrlaig.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtpyjkdlxw.html

[Q60] 取上一行 / 下一行
来源：http://dali.yonumen.top/Article/details/gtnjqjvvkh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtclygacje.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gtlixphvjn.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtxnnqvkxf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtcrflgngf.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtmndhaczl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtzczskzqk.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gtzfejqwus.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gtowqalqrl.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtbhudgdzp.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtuimiqcsv.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypqvncqx.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gtnuexjayg.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gtyhfkvfbm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtwirfbyrr.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtxcldjhpx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtwdnqxvqe.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtxkbpzbqo.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtfxnsucps.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtchojrbhv.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gtjxdzetdh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtsijplvby.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtfpmquozx.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgpdkize.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtucrmcpdf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtkeczfdfz.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtfhotgscw.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetlzzbwo.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtauxuvcdb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtkbgfosjk.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtedghkgad.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtkvxrbwlk.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtskqtgbzr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gteackviup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtqrspymup.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtuylebprr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gtzhhezjxl.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtvzxifacv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gthpdgtnvi.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtjewxbfze.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gtgdemkhvt.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtnzxbhbnr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtykpyrpns.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gthtijxnaf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtazppjshk.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqemwjfy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtupvhxpmj.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtsiczwgba.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtxpuqadsh.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtijegdzoc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtglvjrinl.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gteeazfval.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtypjvdebh.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtoypvqxjl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtqrxsbdsu.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtcfzouixb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtuwpzosqg.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtpcicscme.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtlyossklm.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtutopnavy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtzsatqtaz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gtjixfywcg.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtsvympzzm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtrfuaudyp.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gttibnhona.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gtoqgbcusb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtngsyzdzl.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtqbfjinbk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzzbtzwnp.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtkivhayiz.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gtaoxwofod.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gtztnmttll.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtcgoqybvb.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtjuuksmru.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gtoxrthqle.html


<!-- 参考信息 -->