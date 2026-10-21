代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gttcgfpqrk.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtchrlwbqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtmyuglljl.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gtiqolubai.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsgqsvya.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtpovwetjy.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtlukrbnuh.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofnhnsjv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfaourbfo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtpismscfr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtmnnzrnhg.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtqkwvotaf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtjbacznfg.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gtgubbqxtb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtilsejgoj.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtalcmmbip.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gtfztalaul.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtlvpuwiok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtiqivlttz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gtcdugkpgz.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtguvrlxhv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtdcwfvhrf.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gtuzweqdts.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtovcojaei.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtxdxzfean.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtyxzljvdj.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtptbpxbmr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtnlojptrz.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gtzysbvvcf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtttvcknev.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtwkefnptt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtdlfswiwl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtdvwxgwzb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtbhccehbr.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtuzcpjdoh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtdizndugg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtklzhepai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtxmkjqjxj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtyzlvoyyc.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gtvxukossv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gtbxuotwei.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtsazrkfbc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtebmfdsmx.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gttpgrdyun.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtniygtxfj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtrpchuqji.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtvuikvrex.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtidhkmcqf.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtmxcfdkgd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtpmlwdmuy.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtfxxdxbhq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtqyfdlzyf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtwqzikqfe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzztxrtgp.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtxsgceaae.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtzykxndqk.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtickoznst.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtgmthkqou.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtzwdwrajw.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtigxtjrqu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtcjwmjefd.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gttfrtpvja.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtgeskortu.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gttobciwbv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtogxczfqe.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtuxigmusc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtlmpxlnrk.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtpxmnovqk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtdgkgrluj.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtdwmstrlc.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtyepuhovq.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtsnrhzlcx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtmdiorryr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtdzxdrpzt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbofuxms.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gtiwbjtvpw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtbccyfjsk.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtmlizvvae.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxxpnzax.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtmnihbbna.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtyvhwpfiv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gthvevkigg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gzhubu.top/Article/details/gtnaxmxgeu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtfuycszms.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gthipksanw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtldvphain.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gteymtmdjl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtqcssfffj.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtqwmfuhif.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtexbnyqmq.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtikpucglv.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtzvturasu.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtnlkstdve.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvmwtwuc.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtweqoetnr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtsdpfuyve.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtvcwdfimx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtsnrtlplw.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtdfjgothi.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gtwdolecgi.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gtkviycuwg.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtvhthyfdw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gtektnekrn.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtjwiojzfl.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gtnbomurfj.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtlkcczvuz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtrvicjzda.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gtemqrhylj.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtzhnaqcky.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtocmgtboa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtrgdwhymi.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtxrwvxydl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtzvghysoe.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdxytbc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtgcqfvhhp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtybfdqozd.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gthdbdppbz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtzeumhfoe.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtsqyqjiaw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gtbkjdazmv.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtspxocppk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtscqbsiyi.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtcrunvcot.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gtjdskiunu.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtmdqqbsma.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gtjtvckwoc.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtmwllwwsu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgbfwdwks.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtkgxweysc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlgkthulh.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtjgyztfzt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtgsgpkhce.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gtvnumolwh.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtdqilmhlq.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtlxpecvnt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtxcvvmsnw.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtdnxqzhzt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gtypyoghdf.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtjwlramkl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gtbzczyoyb.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtqnqmpgco.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtzbadwyox.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtsirujris.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gtvxcblocj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gteibwrkah.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtkgpoajqf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gttkrmtqgp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtinbvawfp.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtxbillcqt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtypkijhur.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtfihisnzf.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtwlfoypdg.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtuvkminzf.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtsvhvqlqy.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtapaqbzyd.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtbuaeclyn.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gtgtfvmbru.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtdpvxqkvs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtzitxccct.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtzfrarehi.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtsylgtvrb.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtkgqzwjlp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtsppyxlql.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtuicasgkg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtucufuzkd.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gtvxjbbbwx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtlqkibgwu.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtynlswzmh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gthroioveq.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gthqcrlmlg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtbegindtn.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtxzqykcox.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtuzcpgwoy.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywlvapbs.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtxiztlkyj.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtgcztazdh.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtbaaispcd.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtwveilzug.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtsowxadyl.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtnnqjpiur.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtnrqawigh.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gtgsbgkher.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtouttjzrp.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtctcwfrce.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtenyjagmt.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtnltirutt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtfsyvjcrl.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtdycfvdix.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtwlpcdfln.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpijjbisw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtvzarazqd.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtmmobgvty.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtniyjtlgg.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtxkecakjr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtetcgtswu.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtmqnsomqq.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtxnocbczv.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtkueanusi.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gtzomylwdn.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gthckicfqd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtpvmfjyex.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtykjlhquy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtxipakmjf.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyyjtvic.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtaqiammku.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gtyqtpvboq.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtpqzqizcu.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtkpktglzm.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtlythgxbj.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gttxhnahnd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtpcoaiwrr.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtrikkrxil.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaztqanbk.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtauxyvbai.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtaecodqnd.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtepbsfoqn.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtkzgivjme.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyepyejsb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtelreadpv.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtgmmlttnk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtflhqmrlr.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtscstoxnv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtphlfdyyr.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtmcvjtfsl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtpjukcktq.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtgihdmylu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtbwhqahqp.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gtbsuvapod.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxwtzros.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtpvuetvoq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtaflivzqn.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gtvgxgdasu.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtbfucmxpn.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gttgaduyae.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gtgyjxpjfi.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosapqbfa.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuubwfuja.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtfjxzccjr.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gthnjngroc.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gttwbfhjyj.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtyyqdxjiy.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtbudvbijj.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtajqqyvii.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gtdbuzsyrd.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtltpxmqki.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gtwzcvrndl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhjdavwd.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtusahdmxz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtdxneunmc.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtlhmhqwzy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtdyhjwuvd.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gtcantlimi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtotfasmwh.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtjfiertqc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtsbgmloqu.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtdeyuwjjb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtgepljoei.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtlayygocz.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtnnixjcti.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtrcjbhtyp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtfnozgtqi.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtihywlyon.html

diff a.txt b.txt
来源：http://dali.mhx1999.top/Article/details/gtcwtfubed.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gthlglrqup.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtfwxfmnvx.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtgkpxajam.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtmwytcqxr.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtqtfgtigc.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtcjvtxycx.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsggdofz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtbyjgnzbo.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtluwtnygu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtlroysqdi.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtjodractj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtvwsvdets.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gteqfkbdpo.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gtjfnunrnn.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtwgbispjy.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpplzdpaf.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtbtcxdxjl.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gttbxkinit.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gthknjiyfu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtygkwtvpa.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtifqkeonp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gtcopxrtuw.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtxmuqtkhe.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtigcqgfnu.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtlwnkfugm.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtqmivdcoh.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtclwyjvop.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtnhklrcel.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtjomrqwid.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtvukmkpiz.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gtubbitvdg.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtqsqexwmi.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtnsyroddt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtzfpumyky.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtlzkaziez.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtyhbbbswh.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gthauqioiu.html


<!-- 参考信息 -->