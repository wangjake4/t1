代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gteqpbqtyk.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdlikiam.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtsjnimlpz.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtkobvafns.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gttayabtkg.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtrbcmxmcg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gteefajthv.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtkdgtsvog.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gttwiaurqd.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtbcprfdor.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtothdfucs.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gtrgqvnosj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbynekfr.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtnzwjqdav.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtnptpmtcj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gtatbkqolz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gtlspqapke.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gtzanulxgg.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtumyuovpz.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gtnefcxfue.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gtoyousiuk.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtdkeyczwv.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtiwwprzic.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtylchjquq.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gtvgnqyqvi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtlsxabaiw.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtsqjwrigq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtkddnzieh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtkvrcutgv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtfgiijgco.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtvdpbdggd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gtogcsviko.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtossppbkj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtjrroeipx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gtrixfddhd.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtiqcjwtan.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtewrdpxyj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gtqybkgliz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtlyzlryrm.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtunrmdsvx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtougamzlh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtijohcfmj.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtfoezuogz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtsbdrzxhn.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtgwpwimnl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gtsmafqctk.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhgbstuj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtkiteymal.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtklgpnjar.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtzhfmqvpm.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtwvahlsbo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gttohbibod.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtobidzgnx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtxpwsplzf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gtkbohmxqc.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gtvjhrmsxg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwlundxx.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtpndlfryq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtspchicot.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtsagffluv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gttdcayhew.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gtrnxknaeq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtrnengaqc.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtxktjnufy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gtsoioezjh.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtnzlydsdl.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtuybzumya.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtolrixwbi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffcnadum.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gtnlxumwdh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtlfkgqvso.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchmagaql.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtqznzeiwx.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtdbxdwymb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtqarukrgv.html

[Q59] 分组内累计
来源：http://dali.shangyingyoupin.top/Article/details/gtqmkltwdg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtvthqhjzn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtblcbwfof.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtrhfbysls.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtkhxpxpfv.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtwkzuxjju.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtslycsmsy.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtsmrdxkgq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtiuqqsxmo.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtjrnggdde.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtfnkxfnzc.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gtkfmnahmp.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtffnsrpzt.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gtrnycktnf.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtmxraymkz.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtfoftdvgf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtqdtjlmhd.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gtmmfviijz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtftdqvtfl.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtgaoqbscc.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtffhlndnc.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtucdrseju.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gttgqcbtvf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtatwntzuk.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtjgeggmor.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtmjwkgzvy.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gthndwqhng.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtirborcyt.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtbchzohtf.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtpbijiwmq.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtenoqydzu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtajbrtqmp.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtjwmzhtdq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gtqvftxuas.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtciinspce.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gtdzjqkpkh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtvnxcummq.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtorrkonbo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtctvdiimt.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtusnrspjo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtzptuwpls.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gtwsrgixie.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtwzokdvva.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtltklrmhc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gtykowsjjd.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtlafkzobn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtdoqpzxls.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtsgfcnmby.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtnoivuwcm.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtypvnzvfm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtsnjzzkvt.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtcxmkubxd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtijpkuxks.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtorlrkxrw.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gteokbjeuv.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtzynbtubo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtwgvpxyhi.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gtzromerxe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gtklpxayfm.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcjobrkv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtwkwjrqpm.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gttzruylhp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtxbkmhidm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtfqndqtxv.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtrhnzrwgm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtxcbqvarm.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtqmkblmop.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gthlzwkadv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnewbrvwu.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtynxrmmwd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgtqpsnyu.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtbebyzxlr.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtsnzkpvcw.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtztnpzzvk.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtelcverya.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gtllfvniop.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtelhzuyik.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtrgpmfxfq.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtyrbgnjng.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gtixrrawxt.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtagxpxacx.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtursxinzm.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtamiujsbv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtqrirmogp.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtfkweymux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gthwswqglx.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtooculeij.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtdmxglsxn.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtuxsviwzn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtltsizmaj.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtfwbgvkyc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtjsdbigkb.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gtjuufdupg.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gtmthzopfz.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtbqfginoc.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtbhxautcj.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtxyyshwtn.html

esac
来源：http://dali.gotoacloud.top/Article/details/gthapuxdeg.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgcqtyoo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtzkpdizzb.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtdsrbkzwg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtsmgpmulr.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyknkxnky.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtafxkcubi.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtdimlnhvu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gtvpxisplh.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtpwbbfigq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtdzbjhodr.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtfvupcndf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtaybrrnul.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtsamfcipl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gttgrtxdrq.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtgszlhzus.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtqnkmpubz.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtyybmvzkm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtpycjdhmp.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtebmnssxf.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtibwblevn.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgdozypr.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtlfxzcbvd.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtouycyuvf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtybsoifng.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtyovzxloj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtbzyblvoj.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtqxdehdkw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gttdbsaldl.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gthaumgvja.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtfsybxsxd.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gtavpjbaxs.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtazrwronz.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gteqmrybwu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtrryazsxc.html

[R29] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtnjicgnxm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtptrmulsu.html

[R30] 函数返回状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtwkhnjfum.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtdlqqanng.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtrqwxbgyf.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtxsdybivh.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtnfzusrow.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrgzdcxl.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmpuxlzu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gtzulizylf.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtqnbihzbv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtxswrxtua.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gtolvykmib.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtoaeuhyqv.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtifzwfuah.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtreivrkbr.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtzhgsfszy.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gtnrazblum.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gttyecqlqz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gtjwgpobrb.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gttszmdomr.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtnahowstm.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeucbrsy.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtdlbqdsuz.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtixwfnuak.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gteanrmafg.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtziotasax.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gtnbxvudgw.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gthfccdurx.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtjzqjlzmy.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtzjncvpik.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtmobmlsdu.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gtpasmptow.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtlussmqpd.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtxwdbvepy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gtmlereyai.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtdilpwunx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtockmjcor.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gtpgktfdki.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtydlmqjtc.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtzkupedbk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtrikwanrf.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtfhkvlfhe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtxcmpaisp.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gtxhzdvnin.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtcufxdfbe.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gterodsyhw.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnmjpmtb.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gteufabyyl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gtjufeopez.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtjoutfjpz.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtwyctagxp.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gtfldgpepc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtlavohgrr.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtayykvjsw.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprgabdof.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtefrmlkmz.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gtwfmwidnv.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gtyvdbsmyc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtovcnmlrn.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtdlenctjg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtvpqajvgs.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtpsetkprz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gtywdjssbe.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtqbmaufuy.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gtoemkimik.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtsybybblb.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gteinodqwz.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtbhqgxdpc.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtglutwkdl.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtmpxjhuef.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtffktdvjt.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtbmlaremw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtlhmiuidc.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtishexptz.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtgquoatee.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtttyswpfr.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtoruqmddy.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnrbihex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtsngbaint.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtblcpwjtq.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtvzxvjrbg.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtiedpfjpb.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gtxhhgjxcv.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gtnktljrnk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtluoxbyxu.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtgajexcdb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtbdcgigbj.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtjlchoftx.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtahavzimf.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtavuneikm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gtruhlxxgx.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gttdygyyyd.html


<!-- 参考信息 -->