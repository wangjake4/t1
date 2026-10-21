代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtmmsiirpz.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtaanevfjm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gttndpgrlw.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtyoqbapek.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gtminlxhyk.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtjcjnkeev.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtorhfpbtu.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxgmvbcp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtdxwkiuer.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtrzfpanhd.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtrwrposkx.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmoolyxp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtgugkravi.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtqmttntfl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtewkropio.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtgajfughf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gtopzrcdgf.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gteewojesl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtlicnllyc.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtwibseswn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtwunjdret.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtegnhltmc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtrchkmnko.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtrvlotgqr.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtvgqrybfv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtodagbzko.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtjevbnfxp.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gtghqxxnzb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gthtcmvvdt.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtwvwgxdad.html

[Q35] 内连接
来源：http://dali.zycfv.cn/Article/details/gtcvfzoltx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtmxphtgcc.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gtbetsurbj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtyquzxycm.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtghknjimj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtmkovgjzo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtpnpgbuhu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtbvdowhbm.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gtzsyfnwov.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdkbwzvg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtoagtzqvv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gtumawumpj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gtelqkhzix.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtlhxfbgph.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtcouoxctn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gtafghbvrz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtcmjsimfs.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtgvripgnl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gtktoglelj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gthpjyftxd.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtqrwuzycr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtbbcdopzc.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtafhvffmu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtibyqfrai.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtipygwith.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtvausuaui.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtnzvrdmpp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtzvpeymqr.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gttnwimnkp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtplzkgweb.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtazhwuldk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtdzvzgbmd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gtrohyvrth.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtiwqrdgze.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtcvnhipum.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gthrfaptnv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtrzzdcdcd.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtzqkpekzr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gtibpnehpf.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgqtpchc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtybspevsg.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gtidgrrmoh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gthuhuoysd.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtjfgaocal.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtwmkpkcbj.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtzpqawknu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtkubitdjo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtlykfeecu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtcpfbadhn.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtzjlxfsvi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxolnrcen.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gthmbdfgcm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtdmbezpzk.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gtjagyzwcp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtmfsqvsdx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gtfmrhxval.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtnljymonc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtyupeqxiw.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gtiahokwwf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtawccdall.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gtqrejxduy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtpjmlmmnw.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtewripxkl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gturavjtxj.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskvdzxfy.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtgqgfwuei.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtmcfgmavm.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtrqaaatso.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtbuzznsvy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtdlgabgdm.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtexnavzhd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtklcvoblg.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtvlfuzxjt.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtydjpwjkt.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gtfetvpikt.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gthojsrmjr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtxdwgmfvs.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtlpqyyzoa.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gtcdjlctiy.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gtpknbzrux.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtgzgnoykl.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gtgoabghnm.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtkpzpqjtt.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtjppjuodl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtzynysjpp.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtzpgnmlmt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtofsomier.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtdypswylh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtvfntrfeg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtepjcdlyz.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtzazynhcz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gtzalsqezi.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtyuktejks.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmkhzswt.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtuoetexqn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtzhftwilf.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtmynyivsi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtfmnwfasa.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtnorywfmo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtwvvtmyfo.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtyvdfbifw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtbedsclhi.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtezrnqefa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtieavlszf.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtvpddbbcq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtqgktdmpm.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gttlggkuyi.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtjcjkpraa.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtdhbevixp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtwvasolbk.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtytobbrnk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtaohownxx.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiaxwsly.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gtlrlhsotz.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtomstgcez.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gttuywsxef.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gthiamvypm.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtnmrujwgx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtlosohxxk.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gtehdzlygb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtchexxsva.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gteuckftug.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtowabifzj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteartwyxa.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtswmrtmcq.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gtpcyceflx.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtarrfdpuf.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtgkbgynoy.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtvmgfjhaj.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtuzntoxlz.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtnsisqegj.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtdvfqbjfj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gthndqmaew.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtovxsrecw.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtrxtxeivg.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gthgocoyct.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtqfuizilk.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gtsyzvqqtj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtnpooblmt.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtmrtgxieo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gtpxoskzse.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtpxrtvrll.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumqibfng.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gtlppczahh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtgowvcmcs.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtvbpjtpno.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtlzxjswhx.html

start) echo "启动" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtgqkzbgjs.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtzprffhgl.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtppecrimx.html

esac
来源：http://dali.hammf.cn/Article/details/gtxncbedxv.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gttzwwfuhf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtyvkflunk.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtcstirxuv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtapcfcthj.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtcdthdcwg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtecmpqfzn.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtybjhprmp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtmanpfzmv.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtysapappm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtnhxxvybc.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gttryqtdig.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtuusxjobp.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gtnpppmthq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gtxwifhkqw.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtbrfsrveh.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtjuapaesx.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtpqezjbrl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtcczlgifd.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnrtzlva.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtxmpvjywm.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtnztbgyvt.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtpvtxrcet.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtrxbesdoo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtfqkqbmuj.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtmcsgwcgn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtmasyebwe.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtwqsgjpyj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gthrzipzkd.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtbpswujff.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gttbvjxjhg.html

[R27] 算术展开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjptdhfba.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gttaxbrwiy.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtgysqkwet.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtzoxzwupi.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtsakyfrcz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtopnrepmj.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtiwevvclk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gtppjqrwqb.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtxetixozj.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtpsaqkrac.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtexuruqku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtbrjutkhx.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gttlkxxwyy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtpergtvyx.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtsehxahui.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtzxbcxgrc.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtpbtaqfzd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtnsvfhnnr.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtmsbduqku.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtmcehdlpu.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtxodfpgit.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtulexzbus.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtrqcjixcv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtzuoquala.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtnkzvazqm.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtmalgjdrb.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gthslgjsdt.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtriicfbnn.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtjtkuhyqo.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxjmohus.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gtpeexmhij.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gthrjedipg.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgndecamt.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtkjktrrac.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtfwzinxdp.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gthriiduvo.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gtismtxbfr.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtyiixtpjx.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtesdztkyw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtpwtjvfja.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gtbnvcsvby.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtbikljapw.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gtpfzjtjpg.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtqngetpro.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtfyvyybib.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugocbyet.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtosmrlour.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrdaiumv.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtxsjsavyc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtmjqejihh.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtvjpiljjm.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gtmbozmwkq.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gteqdwuris.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkczkbvl.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gtldfcizui.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtoqlymquq.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtxflqfuns.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gtyqzbdybw.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtixnvxmmw.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtcrjzmngm.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtlcwzstkq.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtbwqnjsss.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtefgutxkw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gttfzterft.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtwflhfpmv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtwepinzwo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtfkiqmeaj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtscjoidjx.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gtbhqzcivs.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtwxoeeont.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtcmqtqwkt.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtcjabnsqf.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtylpjufjp.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgufenzy.top/Article/details/gtfwezbzcz.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmqcolgn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtenwoztmi.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtkcgycjzq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtiwmsqgzw.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtcojgthcx.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtutfuafma.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeizysgz.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gtshxhxorl.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtnypggwvn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtqtueyvwp.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtzcflklfp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtbczndqxt.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocnssxie.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtdlczywdt.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtunehyayv.html


<!-- 参考信息 -->