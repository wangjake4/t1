代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gt2jgeacucr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gt2svwqtgkn.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2ttmkbvog.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gt2znusozoz.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2kljhjtxq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gt2idgvaikv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gt2zgrvbqbr.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2exbnuguw.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2xelxjbsb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2qdpygufx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gt2bzuzsewh.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gt2pgovfpbk.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2pwhhqzjs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gscvljoi.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gt2mcvdvwwz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2hyehndon.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2smaczvfv.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2mfqwezgg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2pyocjvwk.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2kxkovbip.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2cxspwcri.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gt2kzoufzus.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2plqxsnfn.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gt2gtrsnasr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2hmcumjbj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gt2vdjjmowp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gt2krrfdknv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gt2lzlbzavx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gt2velblmrj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gt2wbviyhmk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2zyfwnzfk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2pngvikkg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gt2mjkxhmog.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gt2umnlayiu.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gt2dakddohn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gt2geqxbpnm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gt2yoccqetu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2oflghdoj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2nrpxgyzq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gt2gycvpxel.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gt2wzwvcair.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2iojmadfy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gt2dqrvwiqh.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gt2lfchvjcy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gt2mewfrvlg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2hjqiyiha.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2rapxkvly.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2pnrayfau.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2grfqhkkf.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gt2dxwpykql.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gt2vcgsdadf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2nsorbrwm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvyztzea.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gt2evggqyci.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gt2ohizjfma.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gt2bsavnkmc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2fzzrhuws.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gt2jkudnsam.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2pxvaivum.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gt2hgplrplp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2qjgvjpbv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gt2qnxeegue.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gt2oesgmzhq.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hiabjzci.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gt2hbkkmkjp.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2izrwcrra.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2bhxrjsbr.html

Go:   if x == nil {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kczumbjq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gt2wtdwrkgh.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gt2mcfoupoz.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gt2kijjqlln.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gt2fmwifhix.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gt2irnfiols.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2pttlibik.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2hpqkgoyh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oitxmxsk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gt2lvehkkjf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2qoskcryk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gt2kebvcrzk.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2pqztrunt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gt2qzkykizp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gt2bwdytblv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gt2lqpsqvzd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxzjarss.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gt2clykxhpc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gt2qcsqetul.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gt2cyyejtdt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2phlavvkl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2pojnezwd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gt2adreokbu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rvjutavk.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gt2mpifkvma.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gt2uonuuzkt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gt2nqyxpauj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2nwjaufpf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gt2terfetgh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2enxzdtse.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2zvdsfyrv.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gt2rslifeaw.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gt2euahyvjz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2fxajoymz.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2jirlwlvj.html

amount DECIMAL(10, 2),
来源：http://dali.cheryme.top/Article/details/gt2knyirfqq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjalsnre.html

);
来源：http://dali.cashguo.top/Article/details/gt2zkdsuftf.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gt2bfpljzgc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxmbzcbj.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gt2rwysigaa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gt2kldlubft.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gt2rvrixxqs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofgazvkw.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gt2klsxphjh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gt2qlzgtiry.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gt2budvszmf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdpqewhy.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gt2uenbksic.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gt2dyaafgqy.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gt2xuffmgrx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2vdafderr.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmvqeicb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2qpglplow.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gt2rwlfanct.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2zrhusnbf.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvwacfbl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iocwxqyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcaraxos.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdwzewbx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2sultiyxf.html

[Q14] 存在则更新（upsert）
来源：http://dali.cqqwz.cn/Article/details/gt2uqfyphxh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gt2jqnxkpbv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2ftcnogxl.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gt2fjwcvhhg.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldqgvpuq.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gt2cwlbejwo.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2regxmvhf.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjjooncc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2lmsnbqaz.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gt2oaxyqxiy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gt2xxtggufk.html

[Q19] 范围查询
来源：http://dali.yj202588.top/Article/details/gt2joihybtu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gt2cjyhmhze.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gt2eaxqsvcy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gt2qgbwcrhn.html

[Q21] 空值判断
来源：http://dali.jyoumei.cn/Article/details/gt2dizexplh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2fovyyuuc.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gt2tpebwnfb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2zptpduzp.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2yruoxmqz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2sabqssaq.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gt2cpsbbgka.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2ntsnhayd.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gt2mxgrprya.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gt2raxzmybm.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2hwgqggev.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2vchdzqkk.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gt2vydvuqzh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2iymasedl.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gt2ailosxrw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2duiqhmuf.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gt2ijqaiobv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2bklfoxrq.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gt2eycrlgmd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2cuokysvv.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gt2eymtsksd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2xvvryqnx.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2fzvxtdeu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2obuneqhw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gt2xehxyaix.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gt2zxfqaozp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gt2dsinumua.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdkyvopy.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2ommidfdu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gt2icnwbbrs.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gt2nsxuucvr.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gt2bepjbdaf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2ihgxkvtn.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpempcfw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzjvwmjm.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gt2qydbjvlm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2wzfmqdio.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gt2jnsmptph.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gt2dqmdrglm.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gt2qtmlqkqn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gt2hvxvpkes.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2suiuadnf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gt2iovlmrea.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gt2csutyvmu.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gt2shekfpzb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gt2dtipdkwo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gt2jlvotywg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gt2hyujqmwm.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gt2lcpqvngh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gt2omzvcvsv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnyanux.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gt2mwedtfvf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gt2gxncajwr.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2qwnsxrgc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gt2qwehrvte.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gt2nhdmnkem.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2yxhiiuos.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gt2vukzekmq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2xpqumkjs.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gt2okgwtopb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gt2jerqqqqe.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nplftymg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gt2jvnlmyij.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2pxrvdqqm.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gt2hpiwvugq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2qnuhtztm.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gt2rhoxkqrq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2nnkcyszu.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpsilyht.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuvqayq.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gt2ahrxoion.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbputdec.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gt2arwrmwia.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2tcjcsgqk.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gt2iplwpdxf.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gt2paxsfxiw.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gt2rqscjbuc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2xkdyjbzh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gt2rkentvkm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gt2qupptsci.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gt2rsajulvi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gt2yfjatdcl.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2vffaiyaf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2xppzpefs.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gt2nemnqsbm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2mmysvlez.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gt2jugpnkak.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gt2fxzhbism.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2qjtbdurz.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2zmsirgcn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2vvpeizgt.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2ikkpfkph.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2xxonbbfe.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gt2pxkdfbfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gt2xqzgusdk.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gt2owsihgty.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gt2jqvhdfmt.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gt2xvndvztf.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gt2fbngwogq.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gt2gzfhltkh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joueziya.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipgcgpma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2obcijybe.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrsmnqee.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gt2hhqrjdhj.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gt2esrhfbla.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gt2uknnxrgf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gt2nuikkuer.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gt2lcvwiyrp.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gt2vssosvrl.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsezqbzu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gt2dsizvddt.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gt2nzywgzgz.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2ikelqydr.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuuwawxj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gt2oddpoxim.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzqlxrpd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gt2yzvpemvn.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2jygakroo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2owlpqnln.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2zxkfhust.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gt2fjtrdokp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gt2xqjzgrdx.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gt2duekvzzy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gt2rrvizydx.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gt2mljixtey.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2xkdeshwj.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2yhshxgmf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gt2ubiqrnlt.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gt2bxhvartu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2qezlifqw.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2pzbbxpms.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2qzimdyyu.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gt2iqvfaawm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2rfdiyizf.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2opnqxios.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2uivlonzz.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iojubblp.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2pfskbkwh.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gt2qjzdtqub.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gt2irlxszwe.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gt2dblhnvxu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngpmipub.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gt2aljiowqw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gt2lrflonvn.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebzbwrsc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2kyewdhge.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2offehpgz.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gt2xyxyhnxl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2emyvneia.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gt2mymzlgqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2mxadkdzq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lqvydbbd.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gt2cfyvbzdr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owwnsfri.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gt2akkujgvu.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gt2qsvynzkr.html


<!-- 参考信息 -->