代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkopcnps.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtayhmylwj.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtholnodjq.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtnghdgkfx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtqvwgrhjh.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gteecufcpm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtryxmpofb.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtojinyhgp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtnpjsmngg.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtydhpydia.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtsbmkdphh.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtrlorrmyn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtvtisishc.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gtgotrmrbs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtgdicjfre.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtpufoickm.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtqmvzpzgn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtdigueihr.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtdqcoajft.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gtwywgypje.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gtdgcpkveq.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtfefbqvuh.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtemznbrfy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtqbwzavjt.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtcyaqmlna.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtejiglmgj.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtyquskrax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtypytrcsz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiezkxeh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtitrbxgsa.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtrwqorzuj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gtmslctdoi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtgdzfswqm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gtjxjloqge.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gtostacxhh.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtaimfehrn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtlhprafik.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtqbgqexkv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtlirhbdja.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtahaoymje.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtvfkhtlxf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gtnakwdkuk.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtlnxnococ.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gthyziiodr.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtbymhmmdr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gtzplrucwx.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtfbgvrhfx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtcgpcggbg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gtjifxehxw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtvggmxtqs.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtwbbpauwq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtvjpakqme.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gthjlimrbd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gtdhoqshhh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtwhgwckbf.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtitbootws.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtdkdygroi.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtjjdrnbyl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtfpwvmsvk.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtelbyecqe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtnuglibfm.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtwxvppvmg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtlrfmzmec.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtlshmfczi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtbrbxfzha.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtijplcyqi.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtdyncydcv.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtrfoztmbe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtzutxilqo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtcvhrikeu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtsxxkvnbh.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gtfpyjauli.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gtmlnicfyz.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtojfuvtms.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtbaybrzja.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtkdsorwuf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtzgocjgee.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtxonpihcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtvfzrkemj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtqvpmgibu.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtsqterhss.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtjzeqoqns.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtbhhnnozd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtuaqnzqhs.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtnyiiqkgc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtujvezyhz.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtxjzvqkna.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gteqpfdyay.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gteiqhmhih.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtdkxlnsyk.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtkvdxpgkr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtntnqceij.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtoslebono.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtazelngme.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtrcoawbxx.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtlzntxnil.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyoqglfh.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtyxuqdueq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtcicdkiqh.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gtjxajxbdw.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtbmabsulu.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtgpejuluy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gtvuurzrsk.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtmpyglycm.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtinwtnjqd.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gticfyqnak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtmuvokrfy.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtgdvwpgtk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtewfwgfnr.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gthsqfizwb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gttzgoahif.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtqqyfcjzy.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtdslbbkyf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtbdxcyqar.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtfzwoqwwm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gtpwdpuwaq.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtfdcirhrs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtylogtptz.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtxcrkypeb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gttvsivqzx.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtwfonzxir.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfbftkevb.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkisolkre.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gtivviiwgi.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtothfvrke.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrlakqqb.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gttgsnicco.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtlkxdsuud.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtdmcrlxwi.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtyeaclrhm.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtbnctsdvz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yangfankeji.com/Article/details/gtmmxvbvbf.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gtrfuvfrnt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtzdhqluhg.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtqjeyxzlv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtxgdivuvk.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtyarthtdh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtohpkffhu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gthuorszkb.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtacflwxip.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtbevmjcva.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gtfkjznwvv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtiiidskoj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbruzdmob.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtoseswhwj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyfqqepip.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtrcydanxb.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtnoejpvit.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtkhjcquwl.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtafupwgpc.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtfwugfqna.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtwvdcrscd.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmsfjnav.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtaaxfncie.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtyoezuinv.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtqpacowjn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtliyekhbv.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdqxsahf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmokzhuld.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtsjhztumq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtpptnbemt.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtrmxukbcs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtuzybalwh.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtjxlheufc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtwmemixjg.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtmjrwzjqy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtthanibsv.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtdsaiogwf.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtzjmphvck.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtzbpmlvzd.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtxnmhmadl.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtrgvsmkxx.html

esac
来源：http://dali.shzxlz.cn/Article/details/gthpdosyzv.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnxajvjlf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gttbuatuon.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtomekxtle.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtcrigcpwd.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtmdmiirek.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtgabcvkvw.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtlsqszjfz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtpgxavtoj.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gtqfjynlrr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtzjuivvfa.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtgugzlykb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gaohongyu789.top/Article/details/gtuukvyrzd.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtwllifuuj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gthmnwnjhe.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtfacnjuzm.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtabqbvwnn.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtcheethls.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtvgcchalm.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gtrscwjkeb.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtwwkvprhi.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtsqjnmldz.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdpplkhs.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtssdihcuv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtsxhnnaal.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtlqpzhmhn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gthcgqgrvj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtjuvoxjds.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtibvqmssa.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gtpzsypvan.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtuygxsust.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtdjnwmcyc.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtakaxyoyq.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtsblxwcbz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gthuttuzqd.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtcxqfwvtu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtvxvgndim.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtlkvcavpt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtaxjebvft.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtaxpzkjkv.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gttubiijky.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtrdmpfivz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtznslpedf.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtktmukzzh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtytifydaw.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtkegiephi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtggcdptym.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtefnrscqj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtzcfghpyq.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtcctxsmqb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gtshltvtzp.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtfvzrqyrm.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gttjpbtugn.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtyebdtkpo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtkwkdeipp.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtnpnqbvee.html

cmd > out.log 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyaqblji.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtswzfwgfr.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtlzesjckn.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gttdkwzdfu.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtbxfjfljz.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtaafazfer.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtkwfzwcbe.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtcjuqmmif.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtucdokegl.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtixqbndgu.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdkrritx.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gthczxlmwz.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtmiyugsdl.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnzreujk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtzmzisvfv.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtauumivzi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtvqgknysf.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtxgplwzzn.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtimxkxdnz.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpupqvxgr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefgzkmtt.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtmdlyhgnj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtumuzvucl.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtebcncgpn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtloubggom.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtjlljqgre.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtktihmnns.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gteuskarod.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtoepplhsa.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtekebxsoy.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtorisngib.html

[R55] 压缩与解压
来源：http://dali.ybcxt.top/Article/details/gtjkfszcsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guannengcc.top/Article/details/gtsonfilyn.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtkxslrjph.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gttcnxvear.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtwtiiuyoh.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtpfenyfca.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpbaqjizt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtoesliwuf.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtngretooj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtjqjmimld.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtvelsgyih.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtgmpfdzbx.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtrebhicst.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtcceztxye.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtkfsfeynk.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtrfvzrxta.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtttwjjofj.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gtubpvgjvm.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtzbczbgex.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtvecacmbn.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtjcbvucjv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtuqwpnpfn.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtgqkamxpr.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtshlgfjfs.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtwqelljcw.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gtydjkdmrc.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtmykcnsbs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtzlgywdbm.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtomcfubqo.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtzqmbdxjp.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtxkbpljpv.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtfcvhrnao.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtwnprzzpc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gtkpaojeoi.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtcbdzolgm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtxufabibv.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtpzjdcgnx.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtegmhvkwt.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gthjlcdjlp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtsojxxcie.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtffejtvlc.html


<!-- 参考信息 -->