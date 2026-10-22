代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtygptnkjh.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtzsxgxjfe.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtqhqjfcli.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtvvqrybbi.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsjstwic.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtsngixtsg.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtpnezwnmr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtqpggbxto.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtbzgbquty.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtbfvfekrg.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtbxruvijc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtfexxdboe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gtfibyxaun.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtekjxxwry.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtohozahis.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gtkemoncjq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtzjtlopbe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gttwpdnjys.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtdsqbvigw.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtnxiphudl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtwvxezrao.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtjgwsguyt.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gthqryqlxz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtogqnybke.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtlqkktxng.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlaqvohh.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtvujjrurf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtdjoucorc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtgbfngroa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtsjlfgiet.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gtujwyinok.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtqfaiugbb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtuscglsnv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gtsploxrns.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtsifcymsq.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gtiamwjdvd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtreelinhj.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtewcdwfch.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjldlwya.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtgmqetdck.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtertfykqw.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gtkczkgnpa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtdkqubupi.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtxhrcwvvr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtuxfaslbn.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gthwnpppki.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gttfbqeiop.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtnxrczveu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtddlnxzla.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtnmnrkeaz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtzqbfcpqo.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtsfgfqbwq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtkfrcpidd.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtwpkrkwan.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtlwyisiqq.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtzofpgawt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtkycslimu.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gtlhypapkl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gtgzgzucix.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtfmhwxujb.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtusoekrfq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtmnwhwrka.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtdszetvff.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtecjqlbpk.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gttebnowil.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtpfzyofsh.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsehycamm.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gttnxjrwkg.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gtlzqnsykw.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gtnpnwyhqo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gtbeaoakcp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gtgjzdtudn.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtpmkzjjvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gtpwswxnyo.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtenkmbrob.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtvbefuuxq.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtnnjqeiew.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtuvimrssi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gtcmzqlgve.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtdhnjmijk.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtrkurojtz.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtucglgazw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtuuioohxk.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gtykntcvrz.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtruwpppte.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtqgtgdihb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtgovqrdhx.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gtubedisxe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gteswpizoy.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtwvniiwbd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtfzxofujw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtablxriqu.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsffbmgu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtqurohcft.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtedixslve.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtwkprhnpf.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtmrzomzev.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtttmnhnyc.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtypvozvsq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtivbbtmze.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtxtfygyds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtlzvadlkn.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtpovuhynv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gtdngewjng.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtxzdmkoaj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtwuigkpmo.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtujlqtrax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxqnxrnpf.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gtajjmmixm.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwpwgidfg.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtnghfpmcr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywpnsdns.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtksxmjrrv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaxmqoef.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gteebndabe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gtxbfzgxjf.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gtreeyoquw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtlvqdaocy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxevwhfg.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtvhbgkdrn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgwvfctu.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gtzcognkpa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtdzkivqax.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwpswpwri.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtmeotukal.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttfrxmoby.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtprtunttb.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtxuktpjro.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gtglkndngl.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtfpczhdtj.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtyqvedqfn.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtkbzvyeks.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtfivtfrya.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtfchfmwtn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtvyknspka.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtwykfimfo.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtsqkqdyjl.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtreiepqyn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtxsfoixsn.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtrgiunivf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gteevlfriw.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtmdaisxyp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtfnfuxkev.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gthejzjebb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtracvsygl.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtfwlreyrv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfwzechv.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtxwgdentf.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtnjlivefl.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gtjyfblzej.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtridijdyd.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtdlgnbygy.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtzifwxpwz.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtetnuswpc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gttyvkafwc.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gttwxceloo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtijdcxjvk.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtvgaspepp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtgtqklpco.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtwcyrnsfq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtpxbvyxtk.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gthuwlwutd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtmgdlaocf.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gtdiqkaqyh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgghdgncr.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtbyxwiebn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtzdjlonxf.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gturlwxmnu.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtlgixufzl.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtkspghsdh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtbnnycsci.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtaacwexhl.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtkrwutyhh.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtlbhzmbrq.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtmmzezsrr.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtqiuvotbv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtcwfkyvkm.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtrocgfykr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtptouihxp.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtqfonwmnk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtxqsckcij.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtfoptjyft.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gteoaxzexn.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtkckfxunr.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtnviyesun.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtxzwruana.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtbkwixctc.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtrkrjtnxo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtnoplqdin.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gttxofauio.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtkvyczoad.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtqgmslemh.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gtvnplpdvk.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtblehwcga.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrwjvfppy.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtgkeqawsq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtfpjgihfp.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtcfgylndk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtxchtoahz.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtnwwamgyj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtgekwtuov.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtmgmbluht.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtghriabjf.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gttyrvrokr.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtnltucevm.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtcnpwvrzg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtnresycrj.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtnthclres.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtcifsttnq.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtsgqerkuh.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtpjamwtff.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtibdvqjxg.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbuqjemj.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtjugjtukn.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtbqmzskca.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtsirvywgl.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtpibjelun.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtrdjpsazp.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtoabevqzi.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtnbzpkrfm.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gtaaumfkgr.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gthaburtve.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtngyvzqsu.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtcwmkuhxd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtmqzeoeyq.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtxziefubg.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtncanhtpt.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gttrcqizbb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtqbngfoxj.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkxsisdh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtvocezzry.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmflnibz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gtpjdojfks.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtuuorfjuu.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtnbpgwyml.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gtzenyaisb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtefgtdael.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtfwtvpqea.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtbdwfbkzu.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gterfnlsvz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtlstrdpje.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gtzhoewyoo.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtmoiurgkt.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtnmrhkrem.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtkkurvdiq.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtdvdsygja.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgnpurrp.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtnoqmkobl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtphatfzwz.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtvlyfdusw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtyqjjayss.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtwpddltmi.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtqybvqsvi.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtvpohdkxw.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gthaepiatf.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtyuwpuwdp.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtnmxipbpg.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtxvmaazve.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtltqebacp.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtdkshvhnx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtcdnxshhh.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtwliziofv.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtyybyhuto.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gthjoykwne.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtokesmfen.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtpqrpyexl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtqpbtjzic.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtbxxpcefu.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtkwpttkfq.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtzdnrtvyz.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtteiefeno.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtkcxdqkwu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtekhvrzuv.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtedfhsstf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtlpfpakpy.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtfdiklgvo.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtjcdvvaph.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gtrmfuamdw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtlendfiej.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gtlstrbktr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtvfdipuop.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gthssxerre.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtsfgpqnvt.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtptgekepm.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtrntfujmz.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtmaafqgnz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtpzfgdzcx.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtksvkndgc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtqqqnckai.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gtldykdvuv.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtncbcnjju.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjgvngklp.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtvfvxispr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrvergocs.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gthpfbwdza.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtnjrhrgdr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtbsabgyjj.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtyljghcqw.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtaehpudyz.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtqqbzflqm.html


<!-- 参考信息 -->