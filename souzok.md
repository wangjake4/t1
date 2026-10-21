代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtktijnhbx.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtulssdgxf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtxywwpzxk.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtoqbggsve.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtqcdyduyu.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtmocdydba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtjwoqqiwg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gtxdlpcnjd.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtnkzkxnlq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqfsummj.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gtahfcuogy.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gtiualcquz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtfsthducr.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtxszvalwm.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gthjqkbrra.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqdnpbdw.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkratgoje.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtugdzzxok.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtaecuoxad.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtdkfreejw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzawsbwv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtzybuxasn.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtfamxosqx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtqljbqfao.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgkjeill.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gttoxozcbp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gtkoysnzqq.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtgnvgfhgm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvexkpled.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gtxdplqbsb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtiyipazxu.html

[Q42] 连接条件附加过滤
来源：http://dali.shuidangran.top/Article/details/gtjxnouuuy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtnocoktcl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtfsgfxvot.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtmtgunzez.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gthyqznfeg.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmktjazhn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtfrekxbld.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gtfwjjtifi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmammmvph.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtsnnheglm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtfchfcefy.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtqfpiwmrc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtcfnqfxvt.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtzqtkexws.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtquvsjbzr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtmbtlriok.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gttxxrsuvz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtpkhgdlgz.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gtkmrjcwvw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtwjerjyvw.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtysrkytap.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtqkavngco.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtzwszzdux.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtuqvuhyob.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtckxlepdx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtfdmovufm.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtihdyqxgp.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gttlvcaaki.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtjhrulpzx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvhzuzfg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtwbaznkmv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtdhakjulm.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtnqnwbwej.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtgpbekrmj.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtgeczvmjv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtvhtnhwct.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtojsjisbe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtrmfhzgjn.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gthqkgsjah.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtsqqipdlf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtmtgyhyrx.html

[Q61] 移动平均
来源：http://dali.xuanzx.com/Article/details/gtertwhfff.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gttachrkxy.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtwlnyavvv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtzplikeow.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtdljaaaxs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtintyezrg.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffclrodn.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtqxebstds.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtnwhylkvg.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gtwxnbovob.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gtnidjvqjh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtwkujjqpu.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtsdhlobbl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtcedlyaxj.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gtcuwovagj.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtjbtxgddt.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvipopoq.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtujfpkqht.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtzdkycnlq.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtagvtkaze.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtriovwlyh.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtvhnsiabu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtgkyykykn.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtentpjsba.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtgqmnmubu.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtkiojyvvs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtqpjbxafr.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtxkqgqhat.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtukiwjpsp.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtupwmsbuf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtmigogtva.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbvolfhf.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtybquqaps.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtfehydyoj.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjrkpefl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gtxpebgwno.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtervzseha.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtpcgccbzc.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtjocvxhsz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gtxbmdzrup.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtesswfhkq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtzzvcxthq.html

[Q81] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtuefhkhew.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtulaagpoo.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtdejakedg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtyazsncij.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtsurbaxaz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtldrqzntx.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtqtehfuvc.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtrkqkigcb.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtzualuyev.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtmvsuookh.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gteidjzlar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gtrbqeexjn.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gtflbmpjkw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gtqssovrli.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiowhxjv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtzxjnacty.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtikbunpdr.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gttaklefww.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gtgcjdrase.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtminxaipf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gtgbomstos.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmqhcbmnz.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtgvxkyxkp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvnekuprg.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtnuqsbfby.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtveacvjef.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtdyqhtpqj.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtfdkilviv.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtgaebctow.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gttbjsitbx.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtjtcomvgz.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtdnpnhdna.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtlauvgxso.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtbzkiltyu.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtavctqewi.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtkzveupmd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtpeumalzr.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtwblvrley.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtjjhkxtzr.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsfvaozh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gteqtvxwxd.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtmykmewxa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtxchbmuzu.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweguvnxv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtvpjbulqr.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtosmrnrvz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtvebkymis.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtpsjysymm.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gtjzitfizc.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtaczaxdre.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtgrofcssg.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gtqxqnmfhm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gtttnmcihs.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtfdkbbtsw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtbxgrnrds.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtiiluvtqm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtwvufltfd.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrkdzsfwm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtjgeudmex.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtolvkbahy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtaixjthqk.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtokpiviqk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gthekjggin.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtvhxjdpqm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtayvparyt.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtzhvyeyvu.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtkkelzggk.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gturifdtte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gttjfdjtyw.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtmywjugea.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtyakqgrpi.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtribdfdpg.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtomgrtsnc.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtdrvzkgwx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtcioevyar.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtgvrgldkj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtsxqlhaya.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtwkukmkav.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyausyrgs.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtisvjozcp.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtujrfonef.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxwumhyf.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtnjhbzdev.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtqigcdnev.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gtgkkfqyds.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtjtnwgbed.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gtkulgezzy.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtkergbsrp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtirimmpsc.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtonwercqb.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtgxoxzkds.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtpxyxfoee.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtgjpscalb.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtlytyrgwb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gtnfkebxkb.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gthebjkpft.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gttnbzlkbf.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtdrarakur.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtztoomjdo.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtmpwinzup.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtevgwcxzu.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtkufeeuul.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtgpjtmefe.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtsslkxgkg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtmjrujtak.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtqdrhptik.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtxbkytlku.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtaewihppj.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtvnylswja.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtjzhyuzjk.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtthupfmvh.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtjzfrnfpn.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtzcwqthzt.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gtjcntanpx.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtzjqgibop.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gtggoapicf.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtxycwgdzg.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtocszfmok.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtoftdwrfi.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtwltkwaox.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtdrlgarox.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gtdsxmuwqx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtoyiwxher.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtxlzspnzm.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gtqrypgcli.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtzzcfftmf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtmtmpzltc.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtipcfzgdk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtapsdfqnc.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtynhwmamr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtxoyffphz.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtfxymarjx.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtwrtyixjl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtqaivovja.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtmzbqoqyn.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gthaugnquh.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaakqxox.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtxijixkii.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtmxswibng.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtbjlvwwbz.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gttlqgzqyf.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtugyxgumo.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtszcitpbm.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtrbzchbfs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtlhgckyec.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtrmprqyth.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqbiczbr.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtevegaext.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gtjrsgzqig.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldpyswyc.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtmhawoake.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtimrawall.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyclnguk.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtokmnynfw.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtxdiwbudl.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtcsqnafxz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtekfojgya.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtqmdzonrg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtykdexkdd.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtqvmdaknh.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtqgjhqqmc.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtgptxdgrb.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gthrvjrlvk.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtdqnywqtb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtynwyiomf.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtkzrxonih.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtgpvfohpx.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtcpobdzsa.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gtnuhkxqlm.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtuxtgrgxh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gtnbnidrdd.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtufudfctj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtuoegpmnu.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtzbcqjfsi.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtepeusola.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiufotgme.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtcmhmnslj.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtxaoeefiz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gthtkbztnr.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gtuswkwkjp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtaqvljuwi.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtvetadeje.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtbcwigvae.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtfedndqnl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtissfvftn.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gtfztzlqxj.html


<!-- 参考信息 -->