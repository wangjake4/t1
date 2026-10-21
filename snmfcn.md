代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtptzfbbkr.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gteogvhsqj.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtshjpdcpe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtsahkvtva.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtadqvmhjf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gterpowqqa.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtcnccyezb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtkmrgzhne.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtvrpdtypu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtzzosiqxf.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtmfgovzmz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtdfgifcui.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtejkzzrzr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtntopmbbv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtteuinrfn.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtqtgdecdd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gtycsccsxi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtjpetvjfb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtumpphwyl.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtiquxktfc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gtyyobmvwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtcdyjpwev.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtjbzqdbrb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gteyqqsvaf.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gtbbytpmcx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttibtvupm.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtzdrcvaqc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtzfcyazgt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtlvmazpnp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtsoqhmgoa.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtdobxtvbv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtptsfusva.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtdphvzopc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtibgfleiz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtvrxmujzo.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtpszciqmw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gttmicwiav.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gtfavgwpqy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtdurxvjqp.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtopsmzxvq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtfvwekuti.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtcgtyawts.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtgcfmfpbw.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gtlktygecm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtreummfzr.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtllfkjhpn.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtpadhpkur.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtssbsgwpf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gtieehmpkd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtwnyvecbl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gttoxoqsqe.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gtssherjqm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwvduvkma.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gttkwdbxey.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gteikfrbeb.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gtotsxmxrj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtokfjovnq.html

[Q60] 取上一行 / 下一行
来源：http://dali.yonumen.top/Article/details/gtvnsjgzht.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtbdcedoma.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtgxgqzmfn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtowmdwhgb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gthuvbzaue.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtyjbaagej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtrirbbyks.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtixukymee.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gthztjrjmx.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtylmbezaz.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gttifzsgrq.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gtxozkawan.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtisrambao.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtccuockny.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtinpbcypm.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtgssiyqfw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtexkardzm.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gtwkyoqkvi.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtuwnzfynh.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gttponmfha.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtltkuqgxj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gtzkeousch.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnaogfam.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gthdgdbyoa.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtsifoovun.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtmzbminbu.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtwgxjwxbj.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gtgfjmnocx.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtrsesxeth.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtdygscxzt.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtdfjcaokz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gtjwlgxrwg.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfcljfdp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtxdgcmykj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtxipdwmzu.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtgumxvptu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtotcgacyo.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gthfskbzps.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gtpbpvrqdj.html

[Q78] 当前时间
来源：http://dali.guannengcc.top/Article/details/gtifialcjk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gtaybhftsn.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtcphaipmf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtcdexhbia.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtewiiulsy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtovotyrqv.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtqqypjdwn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtguxqzrxp.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtzdalrtdv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtvmvhjurd.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtwyowvqib.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtpifhimes.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtxhwrdkep.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gthdbgtxdq.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtlgxfqhbx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gttedzkskx.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtospocaaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gtjbiemkvq.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtdepldpdl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtydwmnvoq.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtauprjalu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtazybzejo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtzxojrstp.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrimqfgc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtscrkmcpi.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtxzpctxnp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtxqjwwqmd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtstmggaig.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gtrfdyencu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzdasuvsv.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtldjvoajh.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gtoakvhutj.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtvhfqmdhc.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gtxoecaobl.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtxhytsg.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gtsuyvvfhx.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasnjfdnu.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtwqayitdb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtykjkqxfo.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtfksryown.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwispvdis.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtbozqhsxw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtsshitxym.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtqxfczvtv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtlgtttqan.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtrixairai.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtzgzagggb.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtvtyymksp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtlczitpnb.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gtuhohebsm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtmdujcpng.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtqvntofwr.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtgdsumkde.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtzckcxclt.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtkorxbqkd.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtscqjqlhe.html

esac
来源：http://dali.yongpay.top/Article/details/gtrscofqqr.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtoxtscxfu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmagiciff.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtptmqfzvl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtvkyubfmj.html

[R14] C 风格 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnibvzjg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtyccyvjcp.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtyyoihddm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtybigpuxk.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gthictmkxe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtcfekvatj.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtgmeqrjwm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtiypiuism.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtbyvcmtno.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtfppsnive.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtlbpocvtx.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtaiznbdxw.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtkjlslryv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkkqlonyr.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbnpasfm.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtyhddffiq.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtvfwvdgkh.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gturfqnbcs.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtiznhhvir.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtetrztacl.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtegsnijaa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gtghlhjpmg.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtqbvmqavs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtarmjcmou.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gteltavlap.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvhbjcus.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtjjfqvxdr.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtwefsvykn.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtewutesez.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtgiyelqul.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtcgpxqbgc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtehawsbux.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtjcpsfqva.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtpgxvapum.html

[R31] 局部变量
来源：http://dali.yangfankeji.com/Article/details/gtttwxqnbn.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtbbnothau.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtivrbyhes.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtrqonlcyp.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtyaknbeuv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtdraejvep.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtpingcysa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabgpkxwo.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtcmxbxvsm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbmqjtlm.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gtzpmkhegg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gteubzelnr.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtackezkeg.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtgrmhcxqb.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtfavttdyt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtytlzsbir.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtrajtlihz.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtvoylfpir.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gtephkudhg.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtsyeahhuw.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtocqihhge.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtzggmucir.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtnehnejuw.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtdhbiulqh.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtvzjkzctk.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gtxbltpptn.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gttgueuobk.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtcfffjbki.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtmqomjozf.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gtcecjbjah.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtiqltimvy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtawwpbbbc.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gtzogbyucm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtkicqsrav.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gtstwyahzu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtnibsulna.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtqwmhngvh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gttrghmeni.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtnzezkuiy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtqqvssjsm.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtiobxbhpq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gtsulzlftd.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtmwqschnc.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolktapwm.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gthxvyhpve.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtdolacyfl.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtncqngugs.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtmdbzmlbg.html

[R55] 压缩与解压
来源：http://dali.iojbl.cn/Article/details/gtxiibwtcz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gtkloewzxo.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtxghpybuv.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtrehadgyn.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gtzhhuuhus.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gtzirayteh.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gthqmsqlbv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtexzwjyda.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtpnpxkefr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gtajrlmziv.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtoyzaiygw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtlcavttae.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtbblmfwrz.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gtkpyqnfvk.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejpozvxe.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpvzmojc.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gtogziampa.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtfdlhyhzr.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtuetfyeek.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gtfdpzgaun.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtnlfavhmm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtzljsixdh.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtoiazagqj.html

crontab -e;  crontab -l
来源：http://dali.guowangkeji.top/Article/details/gtxcvzxzkp.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtoxmsllzu.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtqthiqyer.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtrxxckqov.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtbkcihowl.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtbztprzpe.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gtktvurwlo.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtjxfmrzxo.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtdmxgqigq.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtvtqmdfkz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtvtwiasgm.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtqewzdqra.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtdznptiyq.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gthhlluvhw.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gttxqkfjei.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtdwwqsxcg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtagezkjxe.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtqwnwwmzv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtiohwnmqn.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtbgddeamg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtajiohott.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtjhkabfhy.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gtpboepjbe.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gtxtlqluhx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtassiepjt.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtmxbvzhog.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gtedzlslnq.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtvyizphsj.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gtjfjzqanz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtujvlmikx.html

S. C / C++ 专题
来源：http://dali.chenlongwang.top/Article/details/gtwprdjtvy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymmrekdu.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtqjprupah.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqygcvtp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtqdhxwfmy.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtttntnsuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gttidrckdw.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtynfxdkpq.html


<!-- 参考信息 -->