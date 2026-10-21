代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtjactovti.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gtxpyydywj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gtpbpnecye.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtehkhjiit.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtfxzefjyn.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtijbkglin.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtbcmlnqex.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtyfogihmv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtsmkjhjaz.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtmfkgtnwj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtaacxjeyh.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtcrvokkkm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtushhuqqc.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcdcottb.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gttyrhljck.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtzqsgukeb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtjrcjqqcz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtphiwqmcu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtmhldbmtw.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gtshrejhsa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjnwhdoif.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtmpyzhmhx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtqwootfhi.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtyhimxxzs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtuhqttmup.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gtizczytrs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtjrqclxuv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtydfdtthc.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtojsxbgjd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtpmajwunm.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtypzpgvrn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtddgwtlkv.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtqfypcsgf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtbtpqscrt.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gttabonosy.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gteqzyplgh.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtkhfeemhe.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gttlgyxffj.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gthmyuilvr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gtlcnthjzi.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtsmziiwwa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtyplwjynz.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtsivtfpmf.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gtlqebgpdc.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gthukrufpr.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtlfukycis.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtzuhrotqp.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtaermtfnb.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtrzjreriz.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtqlqrvmld.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtvhdffxcm.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtldcwuafz.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsemujgh.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gtgzpxwrfk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtkjqgogop.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtppybdpdi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtwpntxhdt.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtvnjeujxv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtiebucjqm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtflycxzsg.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtclgdwukj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtmzotlntv.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtyqiyuilk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtckeafhfq.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtchzpfntu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtuwsiojnd.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtlnfhknjd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtjixenfym.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gthmceudni.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtiacjukua.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtrtbmlerr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtkdyelsny.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtshnizsij.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvpfagzfg.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtgkxirkdr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtnsuduysj.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtomtgjjld.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkvueaxat.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtvgxwlnmg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtgdxvdjpj.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtwcmudrjj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtzhzbmrqz.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtlidabfyv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtyjcxrgws.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtjiulfknu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gttgngwxyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtnlckvqdf.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gtypnsupaq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtjjxqgqth.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtlsbbzgme.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtkmbnuoez.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtljiyuneb.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gtwtvbqidt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtchpaqhir.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtamwlthub.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtgzfedjqi.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gtcknssgab.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtbhkupagh.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtxoclzcgb.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtlohjegab.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtzcixpzls.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gtammszdso.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gtvpkcouqu.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtieqkumee.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtpgwzlbzq.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gtgsiaitjx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtchrtoaex.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gtwgwglhrq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtmigocbnx.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcpinbqx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaayzgsxp.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtdyemqyft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtiiqggzmg.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gttapnkneh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtjubjieyd.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtdmhktbjj.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtgdbuvnmy.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtqjfctpvo.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtzmyqylol.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtbwmywnmg.html

esac
来源：http://dali.redwolf501.top/Article/details/gtqrzieekh.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gtwhdwdrgi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gthkswgioi.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtbtcuverm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gthwtlriqe.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gtgaxtgovr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuntqtqhn.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtwdmuzrug.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtlqriqvtn.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gtvxnadcqt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtqcrrgwat.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtombzumnz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtngkpnnfp.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtorqylsbr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtjhaxsnyj.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtmtjfphbb.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtmqrpkaeo.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gtpzyauoch.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gtyexelvfe.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtmkbitayu.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtnmphlmsr.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtwdufsapp.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gtcxjtgjfq.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtqpvyspvi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtshhqqgaa.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtentdxbbi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gthybenlen.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtjhhzwwam.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtbczczwtr.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtnwsfemyp.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gtugycmzdv.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtqvfgfdgq.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtbpgkhgmj.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtggdazczi.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gttsfksjqb.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtbhzugzep.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdezjpua.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtovqzbkyk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gthabkycyg.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtifyxulvl.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtryfrhuis.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqxigwwz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gthdavumcx.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gtqjnugais.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtktvdqvrq.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtnwfscvbi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhivilhw.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtvtvnvjsr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtgnovhqpw.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gthcbarhwe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtjjrztdcc.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gtzstqswek.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtxvodizhe.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtbyulxdyn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtizaqsqqu.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtqvagghhs.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtspkyqvbn.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtrtcwoqyq.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtkyrosdxh.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtpitwxuxd.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtxranaflt.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtyjfynxbm.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtulgtjhdf.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmowsuyik.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtnfzjmicm.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtkibaqymq.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtrlmgwiwq.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gtsgkvbmsu.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtaveyvysr.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gtqgavwvxz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtvxwpliij.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtdpkoflil.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gtkbnizkei.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpqetqdy.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtzrzhguxm.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwwfmezj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtlicnhams.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gtpjwhzpos.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtgbcofktl.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtopwetyao.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gtcaenvxnt.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtpgaesqrj.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gthetrjnbq.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gtqwufsmcu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtsspnuzjg.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfpbiqdxq.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtteknmlpc.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtgujqsfyx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtnaksxvxo.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtaecmqoed.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtqweqwrmm.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtauwwuxua.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtcszarsqp.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtcqakeqad.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtcajgipfb.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtkngnyeij.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gtvgimgfrh.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtvmnstymv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtewwrgukg.html

[R61] 磁盘占用
来源：http://dali.yueranfly.top/Article/details/gtkqewpklu.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtgsxvmfoi.html

[R62] 找最占空间的文件
来源：http://dali.ybcxt.top/Article/details/gtsxvizppm.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gthgxsaleq.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtruvgxakw.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtwdluuimm.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtmibcoaxj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gttgtudlec.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtcvlorxaf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowtmypxl.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtoudpztzo.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtevojmezl.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtcpuwpxlz.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gtcmjtpoor.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtiihmoafb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gteikokmlj.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gttxraecjw.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gtwijgnsce.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtnzemogsl.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtygksoxgd.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtizuwvpud.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtlnagvdck.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtcxobhzhm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtcghmczpz.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtskydvdms.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtxizsstoy.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gthyebsese.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtrsqhylev.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtvwnymgir.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtazogbhfe.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtofkabble.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtndxmnxaa.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtrgqlsxep.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gtfqcmmbnx.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusjysdzh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtadruucsi.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gtfzycstqy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtdgqsjuqe.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gthrjsymjw.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtjbmeytiy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvmerobct.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuhhblly.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdfnmbebf.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtdquozhyn.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtihnyjvou.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvoyuvlz.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtmctgmjvk.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtyulygarn.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtdvvadweq.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gtwrqdnkkj.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gthzpwxxts.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtejryryeg.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtzoxclfhv.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptmjgggm.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtbzvkzwta.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtihfdnktk.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtwurlnkhy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtrpfdiuus.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtcpuvxjvc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtbqofjpej.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtwzzoacil.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtktzkrowc.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyvuuqvn.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtcknoubvd.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzzrhmgf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtxzzybhzp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtbfpvsrut.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtdgugdtvz.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtguckmxlb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtayokqgmv.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gttfhigbgr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtwzhqclap.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtudlzptkc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtdokmicqa.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhlpdxrs.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtoimwyfic.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gtepemyery.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gteogoxuap.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtgqztlzgv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtqzxekvkg.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtkhsxrawz.html


<!-- 参考信息 -->