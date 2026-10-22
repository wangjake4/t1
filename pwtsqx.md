代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gt2tglfykxf.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gt2mzgtvavq.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2hwffmspl.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gt2crixuigb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gt2xamjswqz.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2hzetxbkl.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2qovxhjku.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gt2lesiiaku.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpippncy.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gt2olstdpeh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2pubgqhec.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2mhijjtnj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2biptyozh.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gt2dlrounpj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2loiiyvdf.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktrhwmlf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gt2hsurqdoi.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izahhvlm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2kfonzrlc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gt2btozlsfd.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gt2dtucwfgp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gt2mjpqayeh.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gt2mpmyjmme.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gt2ftpynrbt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gt2gosaigbi.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gt2romqwqmz.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gt2ggowjfhj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gt2gqsirpsb.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzoitpks.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2nwbdkyjw.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2xhijwclx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gt2vbfbzeqf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gt2vmkjnafr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2wxqskzth.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gt2rylgftem.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gt2nfwffvki.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gt2bsmtfnif.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gt2cpvhutvg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gt2kncwpuul.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gt2tchmaful.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gt2zktopbso.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncweouxn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gt2ivdtlzqg.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2uaomnsrm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2pgmomuiu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gt2odxkaaaa.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gt2imybfjkm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gt2olkxhkzq.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gt2upfrvqwl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iklvssjh.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayjgwndm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2veigxzib.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gt2dqtvlqig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2iotbzupe.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gt2flfykaht.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2eqpjqfoz.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxthfeyb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gt2cplkrzjb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gt2nxjhrmvm.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmqqftpx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtoxoldn.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gt2uswqakrp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gt2xbrprccr.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnsptibs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gt2odfystmu.html

[Q52] 删除指定行
来源：http://dali.nanxuanxn.top/Article/details/gt2sppfdnpk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2avmdtnxn.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iencpaxt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2ogmlnpfe.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gt2wgsjdjud.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gt2aoyxaffk.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gt2uivjeobx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2vofefqce.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gt2aotumgva.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2xhjkhcfb.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2wgvgqjsg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2rqnnxpgf.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gt2mqgocity.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofnubbut.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gt2klhijddn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2htbfadmd.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gt2yusurxcs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylftrfln.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2liyuxyvb.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gt2rfxbevha.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2umgrvvdw.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2pewxbrps.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2ucobaaez.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gt2tumgcazq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gt2xikwdcne.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2biefujrt.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gt2fhjmgoed.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2psgcrsna.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2wyslvyai.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gt2fgjfxlcv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gt2dhotbknq.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2lgdspoer.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gt2zbbymbaj.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gt2qnqqkeph.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2ocmqrlfs.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gt2gvvumqbo.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gt2bwxungxs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gt2ujwdhlgo.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2hadfsmcp.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gt2tgilnukf.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gt2mwnbdfas.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gt2svbxhigh.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gt2ggnhriiq.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwdsznev.html

[Q73] 查看表状态
来源：http://dali.guannengcc.top/Article/details/gt2friqwiec.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gt2ynpoqohw.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sczaazem.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gt2mkkjjwvi.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2lgcxsvbq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2yxckehcw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gt2pivhbamx.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2lkrzqnkc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2enwlbjel.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2tuhnepjf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqvlvqoe.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gt2qcowynou.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gt2aeiugmhm.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gt2pqtdrowx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gt2axmssusc.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gt2dfhanqfs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2bwjvkgyl.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2chnzhrkb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2vfquguio.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gt2tsvddbis.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ekghszgv.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgycytow.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2fkiivsda.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gt2ibpceivt.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2dumdncar.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2omgbtrea.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gt2palzjqmv.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2lbbfxvdd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gt2fhtgppgt.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gt2hfwlxhnb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gt2fyupytdg.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhdvuibb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gt2yswkusap.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzslhpec.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2rmpojebw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gt2eycuiinj.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gt2ynovfvcj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcvjhvsk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xluvicsh.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gt2sncwxrst.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2kmgecdza.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gt2wmyqjmmi.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gt2aklanvjo.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjchxoqc.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gt2psrxfrys.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gt2hpacsjxk.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2jhpqgegb.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gt2vndfvduq.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gt2cbyqbtru.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gt2kyguxsnw.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gt2asvjxaql.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2czaixaos.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2noqapbjd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2hzvopndl.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2diwgugkp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2oajiblqw.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqdmeaxj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2umznhhcg.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjqbejlj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2ryhmjdgl.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gt2elfgupug.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gt2knnhaxqg.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2wwethiyx.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gt2ualrwucn.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2nmepcsoj.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2vivouznm.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2enftaciy.html

esac
来源：http://dali.cdnleiting.top/Article/details/gt2vjugzcul.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhswrzsq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gt2grjdtqyz.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2jgmslatn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2pedpeydl.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gt2pxtruwit.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2rpqiypik.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2ksmopjvv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gt2rnqggbpq.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2ekkawbbz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gt2jhnigtun.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2wfhfming.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcmpfrb.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctqtwoso.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gt2ypixopnu.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2oonabsib.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2xubyzwbq.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gt2gjzmxmhb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2cnkvsdts.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2hsbhnttw.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gt2wchaacty.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2btyrggvx.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2bfuthiac.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2aqnmqewl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2vjwrvfrv.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcpclrsk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2dvktedjg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blvtzvwu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gt2iohwojts.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gt2xspdproj.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gt2kbsvecnr.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gt2bovksgtj.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2zllykwpm.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2dtratzss.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gt2bddpcocx.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2mqawrlws.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gt2oiaewqcp.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gt2cmqvdejy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gt2qgilwrlt.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gt2yrecksvd.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gt2uanpbsqh.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gt2ehinzkfv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gt2eddhwoxa.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2ofhamsbw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2imkcvcfi.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gt2scbvoagf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2zchnxnge.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gt2vnxmlcfi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2mmctxarq.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gt2hanquryz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gt2qsxxkclh.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gt2nhaugymm.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzuoujvh.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gt2hqjcddwp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gt2dgbqsxfg.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gt2xveocudb.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gt2dqgpxxzz.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azitockc.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gt2kkbuacvg.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2kluraixi.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2opbapmqq.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwlnsfsl.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gt2bmyllmmq.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thqxeswx.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gt2idjaluzl.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gt2nqbvwqew.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gt2wtvjgjwz.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxpmhvcc.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gt2asithkbf.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gt2jykntchc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gt2zknzxcdh.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gt2zwthwqwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2qftadoyf.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gt2blimtpdo.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2qkdwprfh.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gt2exkkaxde.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbxvmopp.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gt2zuztigqb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2pfaoznzo.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gt2tmugqnvg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gt2cdgvqeba.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2oimcbosz.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2zzwwtsks.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2gwmnzvzv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2jnpxpgpy.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gt2hfbwvaqq.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gt2fxttbsds.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gt2etbzssbp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gt2ndbhlxvk.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2nvbuujlf.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2vlonoicq.html

[R57] 远程执行命令
来源：http://dali.svipenyu.cn/Article/details/gt2qkkjyffm.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gt2jcbhzynb.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gt2zryqobto.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2jorupxzn.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2dycctgwb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2eqhedmbm.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2fecxpjyw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gt2eofzlybo.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gt2tgoxtzog.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2evcfmtzw.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gt2eygrdmed.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gt2edpicgdv.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gt2choatlmk.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gt2toayapbw.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gt2bmqombqj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2ehjxxgzf.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gt2rnvkkmls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gt2qcxqxgol.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gt2bzzccbcb.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpuxvtbk.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gt2gfwmvmwx.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2xvifhyqy.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gt2svohqmwm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gt2ciqqhvpz.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gt2ktngyevu.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gt2oelxudow.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gt2rxqonjpz.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2buikdgxx.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2kbhfvkwc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gt2wvbcxzyt.html

[R72] 等待端口就绪
来源：http://dali.svipenyu.cn/Article/details/gt2uzntudzc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2rhrlbtqy.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gt2kufbofzq.html


<!-- 参考信息 -->