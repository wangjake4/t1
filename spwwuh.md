代发 wailian999

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtychpeedz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gtnxbeubjj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtiwjdtqcc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtjzuwkqsp.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtkdvekfkx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtpntdstnf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gtyngnjfkr.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtqceabnbq.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtlxosoaqy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbqbfhjsq.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gtgralczwb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtercvozii.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtwpuoblku.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gtxvjshigw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtnfdpdlxc.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhenqsoh.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtzxhslkdb.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gttuggfnim.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtvwoavdkv.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gttlwgnhwh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtcyuabmqo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtdlqvoyhc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gteifxuhsk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtopghqhem.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gttferpkob.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtiqutdnib.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gtfnzneyby.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtffwhisjr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtlzmzhfmf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtafwjemau.html

[P03] 生成短随机字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqbxmwkcr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtzosfeipa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtdxkslqtf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gttfmsnjzb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtpnxpdcuz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gttnoklrht.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtilgtigcr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtqrbugzei.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtsjzsrrdf.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtaxpexjen.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtsrndrjep.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtzvcazcxd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gttytyzzbj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtwlncbgkv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtixvfkbdb.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gtyakhsavz.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtaubingmg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtcsyjebjf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtefartsbp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gtjbgltezd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gtbfspodeg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtseypmnwi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtldcxcmqn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtadnfuenw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gthkaymnzz.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtopfjhaem.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtexhianzh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gtjblfuwvh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkfjbxcg.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvutaupxv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtbasktcki.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtvyxclrut.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkisieih.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtiexnqjnc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gthhqleryi.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlyrscqng.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtmasrrhve.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gtmgdssfyt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtinctqnma.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtanbapvgw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtwjqdebfu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtzwnhcpau.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtimwttkph.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gtzciokxhu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtlcbozbwx.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtjbsilhvt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gtrxbedqzm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtpcccbgsr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtxrdafdzs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtjuhrheww.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtjaijchpt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gtmkcldgtn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gttfozecvi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtzpqjtnto.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtizbhjtxw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtwdgiyzdx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdunomyos.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtkmfpoirk.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtevzlkedk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtienaqnzc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtvhbdfary.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtxrxbeonz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtdpvmxadj.html

);
来源：http://dali.tian-w.cn/Article/details/gtncfoqfio.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gtjgoovboq.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gtlqawwplw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtlvtzeggg.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtewgmemvj.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gtezppvchz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtxqalbqmb.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtsbhxbxov.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtezpefrzs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gttuxutcpm.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtimalcnqs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtiimgxftr.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtmctyewla.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtaiztmvpe.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtrhbyjxwa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtngxqvyec.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gtpxhqtezy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtxqnujtie.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gtuqcicunl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtfaenlvro.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpciezxvg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuusuwkes.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gttkuoijvj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtsnbstjme.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtwhluqvqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtzxvjpfbq.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtmkdvcyws.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtiadwbbri.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtsppkehsg.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtnwvoktgq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtcisioyqm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtejplxdxt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtrrhdgwxs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtnudlosps.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtfprebjfj.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gtftzigmhi.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gttajenkyl.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtpwbnkcnq.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtpuantyit.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtpoegjxuf.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtqidavtwp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gtyygpvzhe.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtddhyqrcc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtdgxhdljk.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtfmtudqjw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtvabbtked.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gtarqblnak.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtidxvkeva.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtsmdhmezc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtlspykzth.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gtbkwgrwiu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gthcbvmiko.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtesberesv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtktsfswec.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtvryfkfkl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtylspqpow.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtdhrrmlok.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtadedatgh.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtxinlfgsl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbhdexdfz.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtttwksrue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtkbkytymr.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtdvonvhmf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gthtvzfmiy.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtgxiibfoq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtjsnreibx.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtmakbhpwi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtloqptvvf.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtdzqnywop.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafveanvk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtugjfbuov.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gthftushxq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtttuymega.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gthpqvvnvk.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsapahazn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtvntuincw.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtzpayhjzr.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtjofeqmjs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtigouanhx.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtwgzalkfz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtvgenciox.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gthsiegnmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtucjiogaa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtpkgycgdl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtcbofevkl.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtrdnvcsoz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtxvfaslvf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtfqejwsfw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtpbuotyxe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiobaaado.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenauzdmf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtopnvfmeb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtsugymdam.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbhyfhgr.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gteazzgked.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gtrgiavbxj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gtxhuwdhqd.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtzckgidbe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gtecjjkbdn.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gtzhmxfwle.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hongshengwenyu.top/Article/details/gtckmsyaaq.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtcabxqqyh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtwoewlegl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gttvchiwvq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtbjkzsfsc.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gturubwjkz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtztvopomx.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtkbvlzehz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtdpqaivzh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtkzjvlkuy.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtygnywbha.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtbgzqcgyv.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtnvlbizpt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtutzsrzfm.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtgrallblr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtfyxrucsk.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gttetasibb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtlxaeakvf.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gthkyyfiuq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtpfithdjb.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gttnxmzfoo.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtyupsvtli.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtwbjrkxnd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtklkouvnh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtcskogywt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtibypltdr.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gtqgizcxql.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthwqxztof.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtceemihry.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtwitqgfvw.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtqktspnet.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtecsoyjsa.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtwpzfpiwu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtkgxrvpwz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtzapebkrs.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gteexfcgue.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtuhrnpcma.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtsbrzthee.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtwpmaqixt.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtspaywzus.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtffvyumqs.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtmikkvmqn.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtkthduhxj.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtnlaoklxs.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtazmnvxzu.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtxsmnfott.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gturgfwdrr.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtkqtrfdam.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtrxzuhqkr.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtgqlgfzyq.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkhrnhtz.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtblghxzks.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtstxduahg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtaphsxzsr.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtqkspvnye.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtvesmimdu.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtlcpkdxyl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtbbwgjyvz.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtweiuboyk.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzryputqt.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gtmzuqkwso.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gthgldkpoa.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtfludeqpf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gtcivzntsb.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtqlcfqjeg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtyohlneoy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtwdzoaxpy.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtxhvbhmmb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtpxxeewkx.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtuabtuklx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtdcsijymo.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gtpevifaqy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtxaefvkuw.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtgfqechfa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtjzhyemwf.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtuytcfnma.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtagzzrwyi.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtbrobovht.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfmqwrndc.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtkfodpnxl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gthczosqsi.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtyflbskrh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtazhpzdxk.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtshuykjfz.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtddbydsce.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gtwfchvyne.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzbaoejl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvehnjth.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtrkqutkbr.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtvzbpmkrh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gthqjbtxgb.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtsbsqcinr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtsicndmgz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtkjvkpyoz.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtikwrnmtq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtbquoeyws.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gtqxemwjnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtuvpoliwb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcbacbmg.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtawywjryn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnsugukbb.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gtlpzghqde.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtnklxkzkq.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtywaqwvwo.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gtjmmrhdzy.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtxzgvzivm.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtxoofyauy.html


<!-- 参考信息 -->