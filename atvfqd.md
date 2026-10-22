代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2syzwxkdg.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2waqznnhi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2eixeoowg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2ajnfgdwv.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gt2tokkawvd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gt2wefkzfgi.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2ycnsqeif.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gt2agmuofsu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gt2owpcqito.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2kyptztnf.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gt2aeqchpts.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2jsaabvpa.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gt2haybzzpq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2shhduyxy.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gt2oegthnod.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gt2esdpbveb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouxbhicz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2ahxzslbw.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gt2jzhaqxlv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgzhfwmb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gt2yxxsfdnv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gt2qshgbkge.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gt2wyqvsylr.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gt2tsjhottq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2ljyfzuww.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gt2itchppsd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2tzqcnhro.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gt2tsygdyxs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gt2yqweahhw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gt2okawmvmg.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gt2kkdllyfm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gt2monnhhgw.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2fdrlcigq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gt2umbrasgw.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gt2xmnbbzph.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2hlqdwsvb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2mreyddnj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2nqgaiicx.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gt2mpwucbux.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gt2njfdcizr.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvpxcbkx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gt2pfxzrqyf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gt2urpenhrb.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2ffokcvyo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2fjpgbtva.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gt2yjqhktdp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2xghdmjaq.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gt2jduksmey.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gt2gynvezen.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gt2zkeuiwpm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gt2mrzdjoqx.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2oxircroi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2oiegpyma.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxapdyet.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gt2imuiyogt.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gt2nexntjml.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2mnftufiw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gt2llclloso.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gt2gtiooahr.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gt2wjyxhpia.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2spgvngiz.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gt2yrknhhxe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2hudldvpr.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gt2xwnjdtok.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2alahqayb.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gt2ogcanpyu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2vhoetslt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2kruowhpr.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gt2oiegfhty.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2ckuspuev.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gt2dzbjoplq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2lmtybapd.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gt2bpqcnrbu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gt2gcuqvssv.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gt2wclxtzji.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2svmpkpis.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gt2kcuueyzj.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2ebmuztkm.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gt2hwwvjwzf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gt2hdxgqayo.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gt2lagzgdur.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gt2ycsbrufx.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gt2lffxddom.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2unceubdz.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2dogemywu.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtqimmqa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gt2tzurqboh.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2mwecxrvd.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gt2ypamdkuc.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gt2fndpueve.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmqyaygq.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2appdlipb.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gt2wxjgwiaw.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gt2myueavuy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gt2xjphzwau.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggbvsqtq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gt2mmnrsmbp.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2kjbfmivj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhqgzguc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gt2repcabpe.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gt2obqzxzyn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2seioigkk.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2qjfunmkl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2uzjiwtuc.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2furopkql.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gt2laglkanz.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gt2ezmckjwr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gt2uxrkgdtd.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gt2sdfncllt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2mxyrdqvh.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2hsvdvhks.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2vufbfuog.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqnxwprp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2uyebupgd.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2qrmdvdca.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2mxhlffah.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gt2shfxshab.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upjazvec.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvyrwcpw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gt2ffvzutnl.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gt2lkifizhp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfhnktan.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gt2cjjiqfxv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2fxrjqnxe.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2bdzbujup.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2qcfzdvev.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2xodzdpwq.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqjzhdmi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2wcxgvaax.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gt2cvdxyglp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gt2fgbpgedq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2igmrfhju.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gt2bmokcixx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2qzbimztw.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gt2tekxvqki.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gt2ytxeyapu.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gt2zfgdkyjh.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsaatwch.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfdswhda.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gt2bsjlfuxm.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gt2ymoaubfd.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2iudtwcwm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2ewiblrff.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkjsetbr.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gt2ckjendri.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gt2qyapfprb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2usgrkthy.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gt2mghmjoca.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gt2stlgndmz.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gt2gddteuqm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2pkhfqgum.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2clxodtuj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2pglzerzw.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2skawiwry.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gt2zsdlbonk.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gt2oizidnts.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2cloxwgdj.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2tpgmrrro.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2ebqvihsm.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2xldvpsfx.html

esac
来源：http://dali.fengsongda.top/Article/details/gt2pzaldxjj.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gt2jnhulxtb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2lruvnmmr.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2cawggvnq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2jpgdwhph.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gt2yveanvfb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2dkrgykbe.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2eekqtrjw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2yskockxg.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gt2zgvzjtit.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2kgnrtggq.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2fiepbpxz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2kmhbtbxw.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gt2nexzvkta.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gt2ipxbcqyy.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2vijiwuhh.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gt2gyifxgad.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pibgaegd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2lpsiiflc.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gt2iykjkkux.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gt2dcbphyku.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2dyhngiea.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2jlcadfyk.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2bknwaijh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2zctthuhd.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wslefzyp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2sdilgtyq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gt2ijftmkad.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2oeqahbfv.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gt2knepnvoi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dznceava.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gt2idxqrzdh.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gt2fvpovzmp.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2dgcwnfki.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gt2neyjmwep.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gt2lqzctpnq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gt2fxfzdmgr.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gt2uqkptwzx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gt2mlujqkfv.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2fvvxenlx.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gt2zspzdbji.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gt2hzziylpy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2sxwqisbe.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2pffmkbbz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocbridkp.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gt2qyfqkauz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2iuywrpeg.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gt2sbrocceg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gt2doymfabs.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqzymcie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gt2xmrbjyem.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gt2qahuspjs.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gt2wldwvwvx.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2hrczjqbq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gt2ebmwslql.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2gyslkokw.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2hxqysaun.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gt2xzhygieo.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gt2sqtwzaiq.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gt2bkhtlhog.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2sntnzisi.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gt2yfqhmjic.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gt2gyfmbkmk.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2pknqglkd.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gt2yybrxkvn.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gt2oimgutxb.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gt2byheiyud.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gt2mqynpvko.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gt2famyidrb.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekfhimpt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqbdchmc.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2iedmdohy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2bahscqjd.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gt2yxgqqoyw.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2glevxrex.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gt2uggfaflw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gt2vqdsndcg.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gt2elozsxyw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2javhgdzi.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gt2nkbvzmrv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2wedkrpex.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gt2ucurjpcg.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gt2xbflqhit.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gt2slqsyvth.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcqmtciq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nawafmgr.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gt2oqckcqnx.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gt2gzlsfzkv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2iebzqrbx.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2uufockyz.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gt2nyhuivyl.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2vtfknttq.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gt2xhnfchyl.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gt2kkqhaeap.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjekdztx.html

[R59] 发 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2nvkvsiig.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gt2mopljkes.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2incmozlx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2bmmubrhq.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2eusfsguh.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gt2tahjyhqm.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gt2dlncchjs.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2mgoomulk.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gt2jalyydwk.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gt2tcwfjyxz.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gt2hwnjbyxl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2giemoxlo.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gt2wuqqgodl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2ivyvucsj.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucsswlxt.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gt2hgbonkrk.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gt2eszliiuj.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2qqiesnsd.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gt2wxrodhvq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlezmfaa.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnvesuop.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gt2juuwkjuz.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gt2cjezflzp.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gt2tobwhwyf.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2oqfmcqme.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tian-w.cn/Article/details/gt2iuoeqynp.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gt2jvafnblv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2tsvdvosn.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gt2ywsqavvf.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gt2llibkzrq.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gt2npfbtnma.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2tyyfwrrw.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2ypeggzbh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbusxrwl.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gt2zyvwcgvb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2lgozirlm.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gt2ztrsqpsy.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2sitieocs.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gt2pwnnijii.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gt2tifqtsvs.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2dtmfmkvc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2zthqwgds.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gt2lwtownzj.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gt2vlnjdntj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2nybaembq.html


<!-- 参考信息 -->