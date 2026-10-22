代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtaxoqvgfm.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtretlrfpj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtpsbrstaa.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtjokclryi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gthtrpdeii.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gthudkmqho.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtkdnkyvwg.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtqioaxsbp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtgzgdsnsl.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtzvagzylh.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtenzqyqny.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtuvkpueez.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtscyljcix.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdrwbjpz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtexwsmxai.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtmhaelxgl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtglazrgtg.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gtmkgtivsx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gticirlukr.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtvjgrfqrt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtoowkoaij.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gtmjbiryxl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsxximrx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtwflhcxyx.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gtgqhbmksw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtjasqbdzq.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtrqtkhmcf.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrvrgqgb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gtcqafjppy.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtrzkmqtdv.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtucqvogre.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtncetozpx.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtirlmszbk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gttxowazid.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtrdtwxdym.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtomtottvu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gttcxdbpdf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gttygxtbhg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubcgcpbb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtteizczbs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtuurredad.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtmbbwpnhl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtaoqefcld.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmznntrxf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gtgklyjjux.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtcqqzshoc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsdcuhzj.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gtxqqifayc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gtmkqnsbom.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gteysbeucs.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gtnwkvesyc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtwvxdejwb.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gttoztswjp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtgdzhmtwt.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gtemyftclm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtmwglsgel.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtctxibdvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gttziyswoz.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtgktnqtun.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtsbfvrimt.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtemxwgqzx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtxliyoobq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmdebrzz.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtcizvbkzr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtclvtrlqf.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gtccnzgmcs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtltraafbg.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtrvvzxoys.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtdtlmtzhi.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtpkclyepi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtcnllimwd.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtkhnxtcln.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gtllwoshse.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtwqwhdhky.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtlbgftknh.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtlnntashr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtiacksnfr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtvhysvnxf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtfajnmoyq.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtsgmnapzt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtocbkbmkn.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtvoyvnrxc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtripwrnhs.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniemviad.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtplrpvxxy.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gteycnsndm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtxarjbusm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtlnjxocfq.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtivqcnaqt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtmaeyoofo.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gtxwlhvgro.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtznltsgxl.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtaxyhclss.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtdddfocks.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtirkuwcjw.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtklhzirmx.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtffepyxkx.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtofqkvtfx.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtnzxcxcgh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtppyrumok.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbpvfetz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtmuecvupv.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtcnhpcmcd.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtukcboqqr.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtkboipzwq.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gttxzxybdn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtixhdsmhc.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtlikvbobm.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtlsfvcdqb.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtswiwiznh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtgnzpjflt.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gtiqqivekr.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtacccxqyb.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtqlxxthyn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtitrztsdy.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtkleozepy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzyttczp.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtienfkceu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtocgnbrnb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gturhdbngg.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gthppqjuya.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtaqwkenql.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtyaslgbcr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gtzwlwvwep.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtjpvjjmta.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtjjwgwfft.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtxnftsaio.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtqqoaquum.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtknsdxjxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtedtjtcpr.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtbxkurfmd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtnevdbrsw.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtbkdmvfkh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtlgbvjtrl.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtekvnxvan.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrnworbe.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtupitmtaj.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtykqznlvd.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtjusnxpag.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtwcatnvjh.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtkfnbaztz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtaiartltf.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gttkjshcxi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtxflcmrnq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtewimzckw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gthmslcwep.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtgcfbvasz.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtzcfvwajt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gtfelvtvck.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtwsndagfo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtnwdwgwos.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpxiilcnt.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gtcbprxwyx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxvevcilu.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtghrdwpfa.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gteagaphen.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtwjpkbjfz.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtdxiqbrmh.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtnmldfmnr.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtitmbyzgs.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtryarllyn.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtgsynddrm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtqslpzbgm.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtbdzjqzwt.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtkyptjtyr.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtgyqfcxxv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtdkvcazav.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gtmhysehze.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gtzhbeuxcp.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtlnmrajeh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gthnjxysbc.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtsjbooijs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtdsdqeugg.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtubqzkcts.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtngwsaygo.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtdlkrmytw.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtnzwtufhv.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtxadggvoe.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtzmzwnoxa.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gtpgqiepwi.html

esac
来源：http://dali.redwolf501.top/Article/details/gtteghqsox.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtjnpsjsha.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gtsznjkpoh.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtdqmmpbng.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtujqmdrni.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtowikfvqr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtqogvshyy.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtpikxklxu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gthrzxhvbw.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtompusfap.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtgdkmhspv.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtvmmoejpy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtbkbaberz.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphrjuape.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtplqadxmc.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gttjddtrjq.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtwqmaiefl.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtemtsroyt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtdulhstbu.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtvgcbcajn.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gttwmrkwcv.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtrkwpwwwl.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtoytykdgl.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtgxlksrgz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gtcxlbsvvf.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtmvmilrum.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtxnzcrrns.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtdblpovjl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtdrqoyaer.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtoeuzzpnx.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gticynikrl.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiavnmxrc.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtbqnavnsf.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtasnxbpjw.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtaaqvdcob.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gttnjlpnwd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtqmrzwayb.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtdtckyjns.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyvozupp.html

[R31] 局部变量
来源：http://dali.yangfankeji.com/Article/details/gtxkjkmrnb.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtyvbjsosn.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtkrwkunmt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtkadkgsfh.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtghdyfhfr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtpgucaget.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtkzdaszey.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtqklyptgr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtaofuiica.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtiqzoncbl.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtjnxvisye.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtwwhtjmki.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtllljsoag.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtkzmwcqzy.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtohwbmkgk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtkspscmkl.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtqkfaxnek.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtduxxzvmq.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtqszwklfn.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtepnchvhc.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtpiwpiaoc.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtrgpvydks.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtdoyosrfa.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtvmqaocah.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtmrsvitrg.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtiuzhyhcl.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gtdmbrvpqq.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtslevfidh.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gthmbazqxs.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gtabfmqxzc.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtbbuoroje.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtmmjrjyco.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggbrxydg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtbmtljmqb.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtsgsixrzr.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtpfgvgxmy.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gthfounpnf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gtbzypvlal.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gtunxfgwfk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtuqvdyaeo.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gtloakvhmm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gtmhujsgjr.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtdvwetqld.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtputswxnq.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtmgdadlev.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtvgelpknr.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gttcjbbvug.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtoswqlrcz.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtuiuqcvpz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtvjnmuaov.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtuwmfoyiv.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtwvifqcev.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtoqkegtsw.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtxvipswup.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gtbnyfrbcu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtlobcfpjc.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gthjgcmamj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtawwrudcl.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtmichzdrm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtywomzcgj.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtysppdjjx.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gtzopnxnrb.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtiruhorog.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvongagz.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexdabqxa.html

free -h;  ps aux | grep nginx
来源：http://dali.smart0.xyz/Article/details/gttpdhqtfw.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtocsvjigf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtimzylsfc.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtklnwgtea.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gthzwrgwqn.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtzlgmceiy.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtuixjswrx.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtvzlfnoqn.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtptxuocbh.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtelhjjcyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtwwwzepiu.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gttnaepdtj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtbzhcucqe.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtuosafung.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtoujztjqw.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtrobmvdon.html


<!-- 参考信息 -->