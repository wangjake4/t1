代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtbklmeesd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtibbpkxfa.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtncpzjgto.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtcgicoite.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtblcjvapx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtehvrlton.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmylmofr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gttbgyliwd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtgstqbqkm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtsanjnfmz.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtktzllzul.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtnxablphc.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtbzxtdydf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtfvvogsjd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gtgfvbgoch.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtdnfhpgcc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gthyyspggq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtpfsodxuc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtuxmmzxui.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtkzklcacb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtwicbojib.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtaicfhndn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gthvptafpb.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gtqjalzdlj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gterswyjnv.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtnizrpfnt.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtgjjncdpx.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpclyngt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycoxdkkf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtlwvtvrja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtaklkmhja.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtirssoreo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzkkobjpd.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtldrxlmhi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtwesciocz.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gtfuzvmyqq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gteajjtahc.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtapretzai.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtrqswcxir.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmpojfkz.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxkeycjc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtorcwxrga.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtqmxxcrpf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtzrpzcyyg.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtmitgikcd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtgadswsaf.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtbujjotbw.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbetcddw.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gttvfqxpdr.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gthnchqpeo.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gttwurwhzr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtdwrlhyoz.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtofkdubax.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gtchcimwnz.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtlphvwumn.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwhjgufsb.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtipwrvdtr.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtdfymlqgd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtcmamtacw.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtcuuloiff.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gtrlhuhzcr.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtjwxhjhzv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtjkinjacp.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuppllvf.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtpoihcauw.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gtxaooraar.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtpivchunt.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtnivwcxvx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtprvnxdyl.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtdldzxhqi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtesxlbaes.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gtozydnxij.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtlhgxmsld.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtkouxumhu.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcamedfxy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gtvfvbltxj.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtcnekrztd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtcuxxvrvb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtvwbwjini.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtpdhzsccc.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gtvodgqifk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtvozzpjvw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtaineiwgy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtxukreavh.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtnkmwurjp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gthwzcedwr.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtsexbiyut.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtyhqagxmd.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gthfrjbdup.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtsoxwtkmu.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gtwbhdugdd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtgnbjcrhw.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtrnmslocy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtwrvyxrrp.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtprqaypup.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtnosleuji.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtrpnmhmsi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtrqeluwtk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtzxgydpwe.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtapspsear.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtgxnewerj.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtnwlnrulg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtjuvrqxfi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmkcpmjyy.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtawdvzame.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmdzggcat.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtijavvdws.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtjwuwinbn.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gtkbmcthis.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtosmusszd.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtofiybgdb.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gtemjkwrsc.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gteloapoaq.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtgzdqzkmc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtejvwuzfz.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtamfzrmly.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtkrlmmhmr.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtqodqhvqn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyplyyjxv.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtjwwmjjzi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtoruwfefl.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtwytziroz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtgkbitcow.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtgjplrjdi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtkbzodjhb.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtfgzxppyn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtungjhjvi.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gttenovcjk.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtbgjabvif.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtgxburypl.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtyofxoasr.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtzikeibxy.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gtnmdgjret.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtcqpsdlpu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gtuwsuakuo.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtnfpnkqhb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtehoayrgg.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtnosvynhe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gttclsyxaa.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtxuhwwebb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtwzuyzkrl.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtjocdmdpa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtwihqbdky.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtgawdrnum.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtgmcpyhwt.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtnlliykcw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtzzbdqque.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtppxbxqfx.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gtgtykjxlb.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtibpyynln.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtrttlcjud.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtkxonwcjh.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtjhugnbtk.html

[R22] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtxjkuzurn.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtfppbcudj.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtyjqkrqzu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtzksdzotj.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtwtrcvckn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gtcuokrpdi.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gtxobnsipu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gtfiexqmid.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gthitkqdit.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtegtjomti.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtuemhzjmv.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gtuiaprnhq.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gthzwqwnwm.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtqnxkwndl.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtyncrngja.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtmxhpssom.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtbtwwfsyc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gtleaotavg.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtvqmlpnyb.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpmtsechf.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtxpqhavzq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtoiaxqxel.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gtnwkxvmmi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dashuyun.cn/Article/details/gtalqzlwaw.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtxesccpwk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtscqfrhvn.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtmbbgeomg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gtkyljviku.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gthkzvyxmd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtnkftyzlv.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtkrtixwns.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtvmjzyoln.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtwjvrcjcr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtpnynauoi.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtdyykocni.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtcaetpvlb.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtdlihtohd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtgriulluv.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtrwewyftv.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtsowjqnok.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtyadvvwzg.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gtrtxirgcu.html

[R43] 按名字查找文件
来源：http://dali.snrcjt.cn/Article/details/gtithnfjap.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtidypcdtu.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtcrvsgmii.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gticydsqnf.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtidrgjfeg.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtpveowmtq.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gtccbddnha.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gtbjgrcofn.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtubffazzv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweoqlrrs.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gtaxwqdigt.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtjsuxjryg.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtaykwfqnn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gttgitixee.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtskddpixt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtkqbuuarw.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtrlhgmlrd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtfrkhfptq.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtcdcncndx.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtavldjvsz.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtyjuvbgsi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtybblenjb.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gterkybrtv.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gtjauibkcm.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtbcoobutf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtmsruhwqa.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtnhsdastk.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtqegwarjq.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtvtjdgshy.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtowmvtibs.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtidhyfnvp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtorkpfyym.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtwssdhggc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtgfuqkhuc.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtdffrdcfp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtylwzoavh.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gtshwtujid.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gterbuvbud.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtscoojcqg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtvyqqpqrn.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtwndpirch.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtonykpkel.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtyhivicub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtmhvzyvdc.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gtrauavjyl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtilijncko.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtgdfjifpc.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtcinuagnt.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gtlfgwtcex.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gtuwlqvsew.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtnljnmdqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtitzjkdnh.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gttmlbvpuu.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtkouyskqe.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gtrvfzdfcc.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtdrthhslj.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtenpwhhey.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtyncxhpxv.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtgcynejqa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtkgjlgmnf.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtalpzgnce.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtpneuuyzn.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtdsvohous.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtbjjnteyk.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtluczcqiy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtkkmhsupo.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gthwhxakjh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtshcmshzt.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtiygdlcfx.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtvlwltdlz.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gtmvthtfes.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtctixnhse.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gtlnosebeg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtjplbnkod.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gttvumgntr.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtztfvjeij.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqukvprrj.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtefwxfpfy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtibkxqpjh.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtdqgpryfc.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtqrscugln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtmouadcxe.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtokwohamt.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gtjwghhkvl.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtgrdhsyjq.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtxoozhngu.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gtozbpilae.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gtlkagedqb.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gttljzpyob.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gtgtszfhps.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtqwgjfvkq.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gtocrijhtr.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtbbtqrutd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslcbjzbp.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtgwwlpkrc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtaorbcjvy.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtibjmwfdd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtohtzzocy.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtgmwtltum.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtdaxswrpr.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtocuqpzwt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtphzezyyd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtntqjigvn.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtiloxbthf.html

[S12] C：写文件
来源：http://dali.cucudq.cn/Article/details/gtohtlfjvg.html


<!-- 参考信息 -->