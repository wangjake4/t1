代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtilcajvng.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtpbbmuipp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtypiuzxvg.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gtqcmlsodg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtsqhhmqzf.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtionmqxdm.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtwypueinf.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gteygaabpn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gttknwyvgi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtgflsayuc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtxhevmhxj.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gtbpiqpfiy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtlusdmirm.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtyjvetnhe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtzmfligcs.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gtfjhdrhqs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtgwmwlwgg.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtadtfpojk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtdujpscqe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtxlpztxcz.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtjibjoeyu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtdbsihewt.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gtkhopeqqc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtrqhoachi.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtckqehxoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtwhgjggvh.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtbjhtppwa.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtjjrywelp.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwdonlkb.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrngslatm.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtcfgxanuf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtkyspzhvq.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtcthewgfs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtdwrlqofm.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtzsyfwkwo.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtebbgtaeg.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gttnidwrex.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtyocplyby.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtbqyswzgi.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gtpnbwxrom.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gttvuduibx.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtnbebcetm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtjphwcamm.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtkokmnter.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtiyucgooa.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtbnkxcxuq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtwdpstxde.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gtscmygvff.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtlemnaivf.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtbljlgyun.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtdatjkkpx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtezuprcua.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gtonkvqinz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtknsrylsg.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtubkkegop.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtvkbbmjkb.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtnxkbigjc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtymlwtbew.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtwdvcomzy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtaccyyzll.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwokgzmgf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtkndgdefq.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gttkpatfvl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtfrozxasz.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtyyazhxfo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gthakbwnme.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtgwvvxdrg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthyvfijkz.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gttzmdobrk.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtceqzqjwg.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtlvbrvzcn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvmqfanh.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtqcewfblx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtkvwkokjb.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtxfjyoxwg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtspkkmmrs.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtyfmbplxf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gtfrvthsap.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtsodcohix.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtltyjqfog.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gtesfijqjo.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gtuxxfktnp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtdjyxhpgk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukgqvhcu.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvalpcyib.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkryqqotv.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtufxqcvmv.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtzyyjceva.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtymdnddeb.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtjslwtnyj.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtgrhhxcfu.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtwjigtxes.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtkrjhpfwn.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtrbadphls.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtlgslwahj.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtdkfvjjcs.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gtorvqenyz.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtxqjfcblq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtwypylhkd.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtufwxgpec.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtaydhgpkz.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtvoorajhx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtdwontvwq.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtuwzuxtmv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gttjuddvin.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtulmbfmso.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtdtihpudk.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gthomtbczf.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtxfvpviqf.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtfibodhuy.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtoahypgvv.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtvijhicbi.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtkuztnpll.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtrdydykjx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtaqstrsop.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gtkpqkuzjp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtgprpqjbj.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtsymmfhhp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtcphgkwki.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtrndorqtq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcurlifr.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtqqdnlumm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtzwojfxjf.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvswfqxx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtcyiltrcp.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtzrjfcmrs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzqcyzxc.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtyjrbzpig.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtjrutmzjo.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtwmbjdaiu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtwszneulp.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtowjegael.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcbkghslo.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtiuuewrqi.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtppmcffvm.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtpvaysfck.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvujznygg.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtoxhojkjm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtqvgekvab.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gtxmrnshqi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtmyotjabc.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtclpctxcs.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtuwtvveai.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtnscopgks.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtbifzfoec.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtlqjqokwq.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdudfawtb.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtznpupppk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gtaqskniwb.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtjgkplbvw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtoznvqqoz.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gthifhespm.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtarylozey.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtfxzfevfc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtviuuoeeg.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgusxtqr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtyqjgszuu.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtviqqsrpk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtnuqqjopu.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtxtucvvlb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gtqiecdxgs.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtszkozqrs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gtegaegddl.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtsricrtft.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtppfbvaoz.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtpuywbspw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gthhiamdjp.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtmsqegtmq.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gttbrzxcfw.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtemmclhsu.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtnttnffwn.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtfyefhxnh.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gtyuuzknkg.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtfoeoaaog.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtlrzluihh.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gtpqbabxva.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gttxlwfynu.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtczqqkmhy.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtpsgnmqhe.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtlpptaubh.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtqmzwmlxh.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtjwtzxeey.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtzlskrahz.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtehbwqkid.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtpmuffidl.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtdrvhoaen.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtnvroehft.html

[R49] awk 带条件
来源：http://dali.yangfankeji.com/Article/details/gtmrrjqbew.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gtgpjvsuxl.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtbwtmavoh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyixvjve.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtplyiawkg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gtgbraxtgd.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtjtrfnhgv.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtgetxekxn.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gteqvvttmb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtrsistwet.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtqfgdwspt.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtwgbbjgxy.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtxevlyusa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtaracgqgf.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtpkynlafz.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtgpoaihsz.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtdolswawt.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtpsrhdbah.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrzrrris.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gthoqwecji.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtzrhcieav.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtbjvtayji.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtrrjgtxkl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtbwgudlbr.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtutgodnmc.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtzvhduqna.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtnxdkhtek.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtwmokxbmk.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlemdqhna.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtrxlkdqhl.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtxmvfhpnm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtuweptbeh.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gtckzpxydz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtwezidmcw.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtimlinupv.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtxasamzrx.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gtxfqriddp.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gtrgqsejqf.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtitxuagce.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gteysstnda.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtpmcruppb.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtplsydbne.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gttkmemkcu.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtmmymyifs.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtddmbprlf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gtnpvtchgl.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtktzqjpur.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcyifcpo.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnnpinru.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtqqgnlpza.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gtiwunrjch.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gtaspquezy.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtowwoaiuw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtjktycatg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtjabuwwim.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtmwqeyrfa.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtitkiaotm.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtlhjtveas.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtkqhgckrv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtjytjsbzd.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtichkmkwb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gtjtypbjsy.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtulxzdqfu.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtnkjvoplt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gteedptezp.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtnbpxoegb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthycmwndv.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtiohsjvhn.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtbobkgdhs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtonsleopt.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtpccwdyme.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtsezjxkox.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtwbxpmlgj.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjdmrcal.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtilllqsmt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gttxvtrhsj.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtpcpgrapl.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gthsnmpuhj.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtwhagiaso.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gtznpmqisd.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gttxlxzqiy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtwpitjnjc.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtyhptvjfr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gttabjtoco.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtxhrffirq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtpbxxiukx.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtgyeatbqx.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtvicdpxzy.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtmxrctkbh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrwyufxw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtpxnqloan.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtruhugqvb.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtadweotkj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtvcfbsegt.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtprgjeenw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gtkvschxzb.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtacnwzzsl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtgjobtgtl.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtwlkufcqd.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrefpxtom.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gtzafdwyvm.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtvlwkrcpw.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxpgqimt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtzhusjyjp.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtztdfydgu.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gthwyasajt.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gtdyunsmtx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxhmfike.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtkqquftut.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtvlmskvsx.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gttflcpyde.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtzkpzxutk.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtktkwshwi.html


<!-- 参考信息 -->