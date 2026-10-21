代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtsbfkdvqk.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gtrjulwnnp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtgyjykcqy.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtijipdrfp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gthrmihybq.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtmbfqltsw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtuszukaai.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtqejpgmdc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtfeqcfdlt.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyplxxrxd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtzfwqjvlq.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtmcaapvla.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gtzcqfisbt.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtwimpftla.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtspzunsjx.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gtepamsnrp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtmznoqfvb.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtpveoxuvw.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtcrccfgxt.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gtazmsqgxc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtkanmfvvp.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gttlclphnq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtoepnzkgo.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtuwzpdypb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gttfzutfqv.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gtjvqgdhdw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtcgoawwms.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtbhvdvinh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtfdlywdbh.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtgervkvcu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtjwttpydk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gttxjboaqb.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtrjsugsyc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtgowinjyz.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtxzswyguu.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gtoxmxlmwx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtzpiobfux.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtzqzanqws.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtdbkehlcs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtdeytzmpt.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtcjysrqwd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtegeopxuz.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtvfmkazig.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gttlfanjmz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtwidurjlv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtzgsmcjrj.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtojwrmrnh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtgwxzgrod.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gtbyphtphy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtskkvfdux.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtpxpcxyms.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtjdaqitnj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtvftyzzfp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtxmuudgwg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtbqbxsqbi.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtzmeimuqe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtsgtmjbvo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtqfjfyqjd.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtdjdjtrmr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtirvfikwt.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtiihhhvlo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gtfsbrndlv.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtqkdqrhos.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtjwobojpc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtnrlqmpqg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtdabftrxu.html

[Q47] 与平均值比较
来源：http://dali.sweek.top/Article/details/gtetcsimxo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtzbjgixrq.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtrbofxmjq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtwjrhbfxj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gtigzntudp.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gthqkywgcn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtmsjlggqf.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gtpjzpvnii.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtbayttjbh.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtubrekisz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtsckjqyry.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtiijwsjhf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtozoytavj.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gtjlbmgsie.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyiauqzt.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtuibqjgkl.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtezqaufdz.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtgbslbmgf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gthjtyrojw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsynpllr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtvpieruxi.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gthsjuoqje.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gtvgrsorea.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtgcwybdbb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtymjzzumb.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtqtamwzkr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtlakabacy.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcgyblgr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtkhqjmgiz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gttxjleikd.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtzrehkwtg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtidgvzlmr.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gthdxtgwlo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtmlpuafvu.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtuasenfog.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtscmmbwds.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtmybovsel.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtwgfcbayk.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gttlfdksni.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtzwqnnzpl.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtjeyhcylf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaptmbsgi.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcakmuadx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gttyysjkmb.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gtczwlvfav.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtcmgkdzrc.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtrqbqkhet.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtwwywsqwf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtjurvullf.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gtguhhtwok.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtmvmcfqea.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtwwunozmw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gtdwtfrmpn.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gtkcehtnfi.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gthefehyvx.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtedpywjnl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtgzsxbrbz.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtfeznjsqa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtshyqqfrk.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtwmltepsv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjhfefyk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtjuwmgsau.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtnacwzcmn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtbpbktfbh.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gthtzbwoej.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtpzgmmybz.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gttytfjvkj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtmqcskcpx.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtatsupnum.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtdeqikgwe.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtwdkcxnko.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtlvxnriit.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtcotafcif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtdxdhzpou.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtzfnncnga.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gthtewmccp.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtentgmmzg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gttcuukahv.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtnovilbke.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtiikrocxq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtcjxgmwfk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtsydzey.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gtvdeyiefk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtbgnmuqwy.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtxbphqupk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtvjlkjska.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtmnauwlqq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gttcsxauhr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtaykvigfh.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtmhhcongz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtazflgbfn.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtltywiwbl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtudhcocey.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzxmpgluo.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtnvflgixi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzlkptegl.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtscenilyp.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtxwepfulo.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gttknwqfiu.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtxdfyafcx.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gtuglovjef.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtisxsoxfw.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gtpukkadkl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtgwptztvl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvlwnbae.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtlmxaqhbt.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtnkadvgvz.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtmeqopnun.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtaimzazyx.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gtpkqqklof.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtbybitrlh.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gthqndglev.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gtpefepful.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtmxtblaqd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtaksqkhva.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtfgcuslcq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtvvrkcpdy.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtzdryapgl.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gtbiqhjpjn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtwelwcaiv.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtkmiblsot.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtajkvbgqh.html

esac
来源：http://dali.yongpay.top/Article/details/gtoehsflad.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtyrexcixd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtwutbzhxp.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtbcnsnjsd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtovdrdmbt.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtafeiovdl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtstxxjhmv.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtwatbrktb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtmflceqed.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtpcjcgvkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtulvenzbf.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtvplhsaoo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gtidxxdwsm.html

[R18] 遍历数组
来源：http://dali.sxryk.cn/Article/details/gtaofmdayi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtotvepscp.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtoybvtgno.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtxkvpewbk.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtsklljlfn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gtyxyzhxlf.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtyzxgqazv.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtbrbfpawu.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtxfctsjiv.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtcepmkziq.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtiejvgnhx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtqyrsozvb.html

[R24] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkleqczj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtqcrqphlw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtxnxldvpk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gthddptwwz.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gttebkfiry.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtkjgnomcj.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtasprtuge.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtktdzzyuf.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtsvdvuwjx.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtxsbiebtr.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtsgzsgyrt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtlfzccxsj.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtluqijiuy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtudjhyhgt.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gthxclrqlo.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gttgeujkcd.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtukmgkphg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtifotapok.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gticlnewjg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtohhulsiu.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtawsubvqt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtkkywwtpt.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtyuqxewiu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtnztmzyhy.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtuqkchfsg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtpsiznkew.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtspidaaan.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gtbrogbzmn.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtrkfokgyx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtqzallsio.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtqawoixwm.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtcpesqsul.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtinbrjgdl.html

echo "log" >> out.log
来源：http://dali.jianghu66.top/Article/details/gtoeuoxrmy.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gteugzvmrp.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtiwwcdelw.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmpyovzc.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtzavxperx.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtosgmjqxg.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtgxszfafq.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtwpcidors.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtgrvsyrdk.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gttiizrprr.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuxzqrke.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqmcrqmg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gtptrlwebr.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtyqgflexl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugavrgwo.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtcdpkrjku.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtoswnxsnz.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtvpfdqxjk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtffqbelqa.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtfzxscdpb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtioizytwg.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtfuwyaiac.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtedkaeovj.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtwgnxfyfc.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gtxvqjyjne.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtucdzmc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtjuqthfdv.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtdyveyghb.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtaejhbzzg.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtoeqgxrsn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtczquexpz.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtixrgnrss.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtmamjftgi.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtevofgrvk.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtsyxzdncf.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtetljvvhc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gtpsiqenwb.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtttcwqdcz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtauoctfta.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtnjyynvvq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtbcftlpka.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtcijkkzbk.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gtvrygqnsc.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtiilrmvmw.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gttcgwsthn.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtorytooqu.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtudlgebas.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtbfqidmgg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtlxlnnvpj.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtktwzqlev.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gtaeaorhij.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtyarlsjrk.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtuhavspou.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gtvuglrwuv.html


<!-- 参考信息 -->