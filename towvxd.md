代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gteepujoxb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtwfithxuw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtzsicxnje.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwtulbvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtwndwdrhn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtueexmdnt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtssjwkykd.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtoqvmzpxo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtmbivoaey.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.mhx1999.top/Article/details/gttkyoeelo.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gtrmjvhdhi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtzesgvqzt.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtcvktznxr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtjpdjopfs.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gtravmlztq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtlikgkawi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtakwkwjdv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtrpdtapqs.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gtiaxfbbba.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtiqxqwpwp.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gtnvfjxfdq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gthdkvgbag.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gttdpdqzbw.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtpgadxsac.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwjcctlx.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtcylpnhfo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtwsjygemd.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtjsdyrsau.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtlksfdtbx.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gtetvnqzcs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtbkotppfv.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtxhgayhhr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtcscfoneq.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtbvdyxddj.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtlmuhyypk.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gtnasbokzy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtvqwubkhw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gtsynmrvae.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtauxubgif.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gtimrgcjkd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtcwdbhsqw.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtxpkutabj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtbtceesyc.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gtnsatmaqu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gthlvsahmo.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtzlramira.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtcrxiifgm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtincckqjc.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtanvjntto.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtnnjmebjh.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtlrcdnxgc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtvpkgqasv.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtdcmrfxsf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtxvwwpksi.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtgmysshdt.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtkfklhevo.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gtpwjmqpmy.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtyrsprixu.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gtniarvbua.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtywwbzwzk.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtnljxgxpw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuvvgefc.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtwvtrmhgl.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gthrwzshkr.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtxbybtgfp.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtsjipqhfe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtysjskqtj.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gtimiyjwns.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gtuswsoprv.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtmkkvbugb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gttkizwblm.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtrkfjwagj.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthadmitxv.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gtbkbtonjp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtqmfxdkqt.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtypnsuaeq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtkrbyemaf.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtsushgljz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtagzziamz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqjwonta.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gtniizxzaw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtbhrmxrmy.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtzfkitmwh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gthraivilk.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtultfzyzy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtwngzayzz.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtaddyxnsv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtcuovjxxr.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtspfxmwdu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtawoocixj.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtnplnufxw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtwrozognb.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gtmquoiiwl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtacilkuqc.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtebepyffb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtrhskyaxa.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtdfrjhjum.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtwdeyejij.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gtssgwdzlf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtbdwcwevn.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtorytfwgv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtffjsdgmq.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtadjubckt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtoiqurlki.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gthbzckhqv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtlwsqeeuc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpmxebbee.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtinkztfxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtrnsyfnrj.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gtzldtudhg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gtpzjyrduf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrgslqvdx.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gtfijxkale.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuqcseywl.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gthsqiysak.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgskovhhf.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtmpsrmqjo.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtaclntfga.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtqicjtxkm.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtrwjpvafy.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqetmzpuc.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gthppnncoj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtnshuemng.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtqinhtdzi.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtldbzgtbr.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtkdvuemxs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtrqcdyrrb.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gtfhikhoop.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtrcivrrvt.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtpxscytyk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gttuufjsmh.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtxezxuuhy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtjznxjzby.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gtlnkaervp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtwvdofnym.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gtxokoghub.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtxnauqcla.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtitxdagef.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtztqpmped.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gthgoqudsk.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtmtcvkhor.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtaehbukot.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gttazjlvwb.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gthockvqmg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtmqfybfjt.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtcpylxlns.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gticwcosci.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnuoahml.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtkngxpris.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gthttvssuy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtaltfiyuf.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtmnekehyn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtujonhxsk.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtywpydwey.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtdrxkfpbs.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtwnmewvva.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtyfthhqnw.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtifigfvcc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtkltdmxlh.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbincauh.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkabpofpm.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtzgszdjws.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtnhlgnrpy.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtzmfdamts.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtejhlafyc.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtmmeifqtk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtsaphwwfw.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtojqtchbt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtligwluna.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtzxccofqc.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtmuvodtme.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtpycqxgfu.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtijydhhjt.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtmdhzbhsu.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtuolsnsxk.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtjdheajuh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtwpgwmeht.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtknhkhlgn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtcqpvbwin.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtyzzkquyh.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtzcxbbtim.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtrqjpsdvo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtivvhvwqe.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtqinayizg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gtnsosbqlt.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtbilwkhbf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtniksfiiw.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtyijggzoy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gthvhqbikk.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtovvqdqwe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtvbarmufk.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtsenqlmsb.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtavswwxbu.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtsdmywdpu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtwhtqomxr.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtaskbvwcb.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtzsthvygz.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtyyutgyij.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gtqcfehmfs.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtacaxgtpg.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gtbwrcgsbs.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtxcgnpuvc.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gtzqkayqql.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtjscqyqqx.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtuhkdgfuh.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtchexcclx.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtuyetptwb.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtcubelxdx.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtascyrnon.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtdbotzvmd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtwsgrbtmr.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gtqfqtkzfb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gthfxopjew.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtopthxaau.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtlnzyndgg.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtnjqdcqzn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtdbiquzkb.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtcqqyknso.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtgvxmzbys.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtnnjpggbp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gtphnvzrwr.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtlnokkzer.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtfzruxubz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gtluxxwynu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtgoimsext.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtfzrqqimq.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gtofbyvauz.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gtfreeixqj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtitldjwmr.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtyejwnult.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gtqcaxfdyz.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gthpsxurci.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtrzecudjk.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtydptfwng.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gtrlscwwjs.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtnwnkddto.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtesqrpeao.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtkpabwcpd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtpvnoffhv.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtqzzloqdw.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtofwoinwk.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtxhlvyxzo.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gtsomljtck.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtlyqtflhe.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtdfgopobh.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtphgrburk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gthnoxgbws.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtnewknxuj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtkbenxjkm.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtpnomzwsu.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtuxozkuox.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtpxtzuicc.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtvohpfssc.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtfbnspvjt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtzwwfhbqt.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtlkkpzaos.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtltiquyuv.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtxyamopjs.html

date +%s;  date -d @1700000000
来源：http://dali.sxryk.cn/Article/details/gtdubgmndt.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtuctnqdlr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gtqkexypgt.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gttndynylm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gthvboafzz.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtjyfpipqi.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtdwjdvymq.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtwydgijek.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtzzcbqqno.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtaamxjzlb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtetbvveiz.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtjjhswmbt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtqkbzxocr.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtpbgrtmsd.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtujwcybjc.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtmztxqrtt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtrxlnnxoa.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtdapwstds.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gteyhlurqy.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtkfdwkdbj.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gtmbvertgj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnqjkfasi.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gtidzuqyit.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqmmymbgd.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtgczyejnr.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gticzzoigb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtrzcwjcss.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtvkqvoifa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbdubbpg.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtnfulpgqw.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtpinspzkv.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtelehdshg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtzenzehhd.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtzfbtnvnu.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtozlurzgf.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gttmfeafpb.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gthdzybopy.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtrgwgzlht.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxgbkkcp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtdozcjryx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtwqsfxsfs.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtszxoqfuh.html


<!-- 参考信息 -->