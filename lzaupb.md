代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gteszhnhnj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gthzftyilk.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtnndjwdcy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtaczebjvl.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtnfxkimyn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtiysksvdy.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtforieouz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtlzapulkr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtqgvfwqkv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtakpxnysz.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtocajxtgp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gtkjtzvqdv.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtyswhllax.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtoegcfpoe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtbjltqjkd.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gttlcugvfl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtbrzddude.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gttcjethro.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhwotghr.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtsizxxupd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtmcfioxoi.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtvbfeembr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtglffhxuh.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gtjqairyyt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtagspqmhy.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtwubegufn.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtndburvsf.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtxdskcsfv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.smart0.xyz/Article/details/gtjfzvssjy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gterkadhvc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfvscxtz.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtrlfhxwon.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtnhnurwre.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gtbxohqtxg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtzlpdognp.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtcjgwnira.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtolamnnyl.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtjzrytpgu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gteetrsaqf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtcvfjvd.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gtomvbsnam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtzfopogwx.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtzmgozusk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtsdfrbjgn.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtevqyvtgl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtpfazznju.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtcwerzjtv.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gtfysopnyr.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtyxqmntob.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gtlbftwgzn.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gtpvutifez.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gthekpxgdl.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtjoyuumiq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gthxsmtuag.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtbnvdnypn.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtgtbkrqit.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtpsafppoe.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtsztqcvdx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtnevcjdfm.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtsavngadf.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gtkupnqxnk.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtpewdgcjp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtuvozlucb.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtyxdxjpvz.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtcntxjkoz.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtfthkmlnn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtilhhhxzu.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gtqetpmuey.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtrylckali.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gttdylwlqo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtuowzqqmu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtphsnwxbd.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtezniawle.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gtgvmesxsi.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtiofqciis.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtvaijxbvt.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gtvtulsxsz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtwhatuhsj.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtsfbepyyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gthtpvsbhc.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtwnjvzead.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gteocdbgou.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtwoicljlz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtoipwnpgx.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gtorcocbfj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtmeskacpy.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtulqqdcso.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtmwfuzjpd.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtaataxhzs.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtrjprljxi.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtxgdvauqs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtyywtdity.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtywlbcgyr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtiaczyrzn.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtjsedqgks.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtpvwrmcuo.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtpbttmpuy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtlyenvmey.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gtxfglvxfk.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtduvkeotb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtpiiglliy.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtwvwzzmqh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqneisgv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtrjyostnv.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtsweoeamx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwfbwbegf.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsnarxix.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcoipocr.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtdhqzlnkw.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtzisstzhn.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtohdfcuvb.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtiyelypsc.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyotrhqf.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtywdgzdly.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtasucobci.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtrivjpuvc.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtmnjqyore.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gtgbhueixe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtmcwgpqtg.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtofqeggfz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtlccyciqv.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtcytwkjii.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtznypjyrp.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtlsceohea.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gtfutigcvu.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtfqlpamna.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtvgqnzivf.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gtjqscsfbo.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtqzsgmbxy.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtrpmajokw.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtnzzgcjhn.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtdlithhlh.html

esac
来源：http://dali.fzhhl.top/Article/details/gtxwljtpxn.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtxatrwvse.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtqwirpvvn.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gthfokndve.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtlwfwvjse.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtzelkrzym.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtfzxbtzgk.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtbgghhyjw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtlibiklkm.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtpaakfuwd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtnucsejsi.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtgsrdbnks.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtmfnbscli.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gthakxkwpr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtrhjetfsf.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtbpmypgxq.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtfihemuui.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtwsuiqctw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtkstfyfrz.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gtlnpmzvab.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gthosuieoq.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gtxlmpekdr.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatdkzzrn.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtcdiouwnl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuxuxjtx.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtjvkyotpm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtxmvoxgpz.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtojpqmggb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtclopyqww.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtibnlaaja.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtegqjbalo.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gtknvfhuky.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gteemadsev.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gtmwhhxmwq.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtztuvdjkb.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrewgwjwc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gtjpcgeaah.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gtirckbafd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkecnmkv.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gtownokqpu.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gtoaqockrs.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtjxhagywx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdfkiqmpa.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gtphnodplu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gtefmhigms.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtghhnzomo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtmwnbriro.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gtcivzxolg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtrowcrcmu.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtjohpgxme.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtkoodrrcp.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtutkcqrqu.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtnthqvdwz.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtzidollud.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtcwhbkpta.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyskurifp.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtysfnjgat.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gtiapkxwmz.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gtfciigken.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtbvcyjrxa.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtjkrzbcah.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtxamqrsdl.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtvgyxhuek.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpoxzwnc.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gtklrtkdlh.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtnkwwosji.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtirsuuikd.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtqgufgxkj.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtgbklsznf.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtbefzwiwl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtawwkydrq.html

[R47] sed 单行替换
来源：http://dali.hywenlv.cn/Article/details/gtbbaenewa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlblihrc.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gttomzizdo.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvpheiod.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtrzqrnjek.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtnoieoyxh.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtzpxfdesy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtifwqufcs.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtinqaepyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtqltgslir.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtxyogfugu.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtijwpnyeh.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtgwrxwxzl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtlchonpvx.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuuouzoqj.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtttuygyrj.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gtqtbocxfx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtcjdbskxx.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtxsjhlgiv.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gtoxzfslqr.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtqujhnhtx.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtakogpvte.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtxoqkabid.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtctvjwwko.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtcjkcponj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gtnqjpbryw.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtzfrzxbio.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtlhtzmsvv.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gtowsycgzm.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtthvhbycl.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtmwmkckie.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtanwencon.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gteuantpjj.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtngtmvovv.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtrnawbwpo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gthmxjkaku.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gthktkcqsq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtaxpjfeqg.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtqmesyzjb.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtkecqbhkm.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtazcdmjca.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtttwqgntz.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtzomivwym.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtuksofunj.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtbicxfasa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gttwyoloxt.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gtzwgpgvzj.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtgfjcpqcp.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtvegqhkqp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gtvkiygsll.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtsfqvgwpr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtsnpjgqbg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtimcmqiaq.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtudbjxdje.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtlwaexsbc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtdfxtuyge.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtnagzkwqv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtivsxrjrt.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmwgkskap.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gttfvhodvs.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtlidipajg.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtnrkbijab.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtkzdjuhju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtjhavzwsu.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtzjyqnbau.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtlwpthfqj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtwdmndaag.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtnztydpsj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbnqjbjwr.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtcpperwzw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gteonuwhgh.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtqeehdcyo.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtojbkgrtm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtwzpefcky.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtczyohcuy.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtfbnnfpbz.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtcehrlktq.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtjmjxvoxu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtpysohglp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtyrqdjepz.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtlvgricpb.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtzkcddulg.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtrghplytx.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefhjmrul.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtkzoxrqtc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtwzcjwdwj.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtnaadmfyi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtlelwrfpv.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivzeovuh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gtmxlaadxj.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtkildbbzp.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtglwkpgvy.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtxvfibgwe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtyuaxcttn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtpopgiffj.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuhdzufk.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtpdxuohrv.html


<!-- 参考信息 -->