代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtybsctywi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtwdvghsxl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gturbkjyet.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtjbetrrfr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtwonndoho.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gtaqvkypxh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtsywgiypp.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtxpobbflh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtzzrfeqrr.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtdgsckwmp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtesoqwzqt.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gtmdcoqsee.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtghfuudkj.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gtciyldhuc.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtjkjolzqr.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gthzlcbbve.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtilnmbake.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtwdorlqeg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtjntcbjsw.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gttqdswnjw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gtncqhcqfw.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtncvwfvcr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtfvmcnafm.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrauuvwcj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtnryrxyhm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkszbgrc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtzpfpdoyd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtwvvdddlf.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtpuiclwwq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtbeuxjedf.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtejdyuuyk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtrvjhtdxb.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtqhbspsyr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtpvhkiwrr.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gtkylujvqp.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtaxetzzts.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtzhyfrlqw.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtoscqllya.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtiyutdzkf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtbfrvyhoo.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtcfrfpvol.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtqihhqcaf.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtdbrsaytz.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtdlzxupfo.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtaazsamwz.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtgbwhegyr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtbfelsssk.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtkknnfkvf.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtpzgjtgoq.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtuigygktj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gttbgpuwgj.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtvadbyqep.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtpbxqncju.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtgoifnzmc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtqiypbqzn.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtkdinkrrd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsigpwqlt.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtjjwmyfaw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtqffksmfo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gtzzoozund.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gtbmolclur.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtukeksanw.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtaeufxjcr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtkmrnrrux.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gtmuouarqj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gtlqvuywjd.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtfxijavep.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtckpmgsbf.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtycistuyv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtmeghxndp.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtpjjawcah.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtthmjtgrr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtnybckrbw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtcdquywvf.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjazcwcue.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gttxvenkhy.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtoblmlrwo.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtzblzhdip.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gteuxbxbrv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtmrqebpnj.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtozjkipar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtmuplkpqw.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtwkvddixx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gtbddzdwxo.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtnfazhvso.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorabhdiu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtvqzxddcb.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtlaufyzzj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtuuvaaatr.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtpufyobfi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gtfpxxvyfv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtafwwnxrm.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtstpiepuy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwigwsygg.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gthctafgzy.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gtcdjtqbrz.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gtmdfzwqne.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtysfwonky.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtdzewuyid.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtotdzublm.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gtpnmlbeco.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtfreuqxql.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtfcjtjvlo.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gterckoehk.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtmnjmhttn.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtjszwladf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtlmanpllb.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gtyrmtgzfc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gthrqfzwjv.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtheskazkp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtowfpywfu.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtebdfrnhl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtlbazafiq.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtseghvvqr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbjegana.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtlrlqchsr.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtcdcehfqj.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtlxcrgjac.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gtkilngkfb.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtrlqqexjt.html

esac
来源：http://dali.tian-w.cn/Article/details/gtzitloxja.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtupmeubsj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gtogzabtll.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtbojllbbg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtviwsistz.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtdskpgzno.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtoqeimdrt.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtwlzkazav.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtzbizvmsi.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtayqptvcf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtgaguuubi.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gtfusfxlmk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gtvaryfbhl.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gtstenifwm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtfxemzdhh.html

[R19] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtbnobwxpb.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetbdfjec.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtyuehwehb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtflrebbhg.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtoyjrtamt.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gtmtobnbrl.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtyhmxboma.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gtlbpzrigw.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtkjwcovle.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtizpcnzkt.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtuhnijfwz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtpijgncdm.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gtyteebfrr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtgbkiaigf.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtkrfrjige.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtkgenwtjv.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtgljovnnz.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtpnitoeyk.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtbyssjtqb.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtfvtlholr.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtgptjadum.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gtpmzbnhux.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gtlwzezrxt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtjeaqxgyy.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtkfbhqyit.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtzkgumptw.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gtgicxmrun.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoaaktrjl.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtvvowskhp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gticvnfawf.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtvyinvnvd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtqygsjepz.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtsxrfrjtg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtjtrqykym.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtcospuzcf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtciifmdje.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtutixonbs.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtojnobwww.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gthswbfvrt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gttdtryxlr.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtztaxedrb.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtbgtjcuhv.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmhgplbh.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtpezzevbu.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtcgppiwmc.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtxazvunym.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gtxjnduaoe.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtouqvmpkm.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gtitgcwgch.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtxosavtwz.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtqphitqut.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtdiijjxcg.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gthgvjctns.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtgpziqbil.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtdrbrolrp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtpxtncerc.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexefjiqp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtgcrkinyi.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtjihcnikl.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtlynjhogm.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gthhnxxuwm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gttadrncib.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gtgcqrfgad.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtoiymtlls.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtpfkhzbnm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtntxrfznr.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gttrfidrjx.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gtfubfbgaz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtkgrirrjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtxropddnu.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfdrjybk.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtswcrikas.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtbfadfurk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtiqyivhwp.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtabzdqpsb.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtqxavumvh.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtbmiqlpif.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtgzppetxw.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtwdzfnikd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gtvueczcpn.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtjfpifhis.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gteirmfkfb.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtftcobwfd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtrgofuwpt.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gttkvlgxqk.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gtqbzciylh.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlghluiat.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gtwfpauxmk.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gtqbxzeafs.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtwgvcmsoe.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtsdscxzyj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtsunwqnre.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoieltry.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtejmpjdru.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gthrdxifmh.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gtgxktorly.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtcwyswbfl.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtlbfuqsdv.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtirrxntvx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtcoxndtjs.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtqfgvtqox.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtcmoisfro.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gtekcrhccq.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtuounhzcg.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtifovcgrh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtxuutlpbw.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtpvtkcpoj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtpuyjhvhl.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtdfruevzx.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtzgxfpvkt.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtfsajtdds.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gthdpssoxl.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjrxkjnuy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtwyvwvyll.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhomnwwr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtxcrvxeip.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gthuhjsdce.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gthkzskivl.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gtvmxffgzh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gthcvezwoc.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtoeuhqamj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtljgscelo.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gtdkhhmouq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gtfrhorbtw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtciukjyce.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gthsqvwmud.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrpcoyovk.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhqsnrjs.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtutfyangt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gtswqyfkdh.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtsfiqhuxo.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gthbwamczy.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtvbzkqiah.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtuolzewxi.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtjdfqhqsq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtkznmbewb.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtcooiicyq.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtsxcgvhni.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtcizuquls.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqoqiypg.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtwlcjtsbj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtztngqpib.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtrnqgtpps.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtevvsjvwp.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtqnjjqcrn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gttaswiaie.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtaywkwvwu.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtcqmtsybk.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtsiqicved.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gtpftbuldr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtkkfjpcqj.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtijncgzbs.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtddhkhvck.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtasdppctb.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtzpawbipm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtpcnlpsvc.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtmkxthtar.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtbwhsznlc.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gthmxqfvuy.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gthaqjimzf.html

[S16] C：位操作置位
来源：http://dali.gotoacloud.top/Article/details/gtgtwldfeb.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtlgtcwsxj.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksftndae.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtnescmtts.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtzrtsavlf.html


<!-- 参考信息 -->