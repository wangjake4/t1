代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqvijfep.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gt2czmaikqa.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gt2qyjvulfd.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2ffnumooz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2cvnzdsle.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gt2titwglvc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2ebjrcgsf.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2kuosiyie.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2kxcvkomp.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gt2zuupugzu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2mofefwbn.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gt2itaynwlz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2jtktauge.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2phreabsh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gt2rmsbrwey.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2bojjgvfz.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrsctmri.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2nouijuiq.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gt2okiavels.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2ghuhfclp.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gt2rwfdgtny.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gt2hijuczxo.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gt2ikptyckf.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gt2rtinibuy.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gt2pvllopko.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gt2ankvkfoa.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gt2oqspascb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gt2hqkapgpy.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gt2qesqalth.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gt2cyfacrmi.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gt2pktcojuk.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2zyhgsohc.html

ROLLBACK TO sp1;
来源：http://dali.bjfxy.top/Article/details/gt2zsqxoosj.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2vtaebroc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2ctsfuqpq.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2ymdedpig.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2tqtogart.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gt2smygtjom.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gt2osicjbys.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdwyappc.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gt2vclceqsf.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gt2uehbbxyc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcxjyyei.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2wwksjtcp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gt2wukgwygi.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2rqiipoek.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2cqaaahzm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2nsetnmmq.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixfigyxh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gt2hcfkunnw.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gt2fmhxirdf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gt2miegfpnz.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2othhhgbj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gt2pqnmzigw.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssykhqte.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2wttqrdas.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gt2ypafphty.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwckzorz.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2nkbtzwym.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2hskiuesi.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gt2ttdwpexy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2xrykplwu.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2qpiirpyq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2aiqwrrmi.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gt2zppjnjys.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2jkkafedz.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gt2itwwdefv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gt2ulxldokz.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gt2lygbjjel.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gt2niazwudk.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2luktuyvp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gt2znqsdapw.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2zzxghswu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gt2bibptubh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlhumswv.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2ltwdvpel.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2vhmcnuii.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gt2cwnfavcs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gt2zmdjrqim.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2eijrcgid.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gt2tliyfuet.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zewiranm.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2wsoiiphr.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gt2lgpttdux.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gt2zvkmtmng.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gt2bpczlrjt.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2makipdeh.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gt2lxwrlsjj.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2vngmbnqw.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gt2gclifxta.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gt2xdgyersa.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gt2xjnddnzv.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gt2yeqbqwls.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2zroufzgp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2tqenfega.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gt2wrmkewlp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gt2jleelibx.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gt2mviastmp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gt2xrtcjvct.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeadopvk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gt2rismqovz.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2hshbtaoj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gt2rhkndmck.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gt2dvkvpoaj.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gt2ikwixjjf.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gt2mnmtgpas.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2cnxdusqc.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gt2udhnygmp.html

esac
来源：http://dali.yj202588.top/Article/details/gt2rgcaisic.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2uphhcdgk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzsgsfbf.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gt2vqemwpyd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2mxdqiume.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gt2xxdgpepz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2cymeyofy.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2msfoeplj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gt2fkgbcydm.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2jugogqgs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brvhrcdj.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gt2qchcshze.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gt2hkhuyfdk.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gt2gbwkzcgl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjomyeld.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2vcvjkoqb.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gt2inamfsjk.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gt2bxfaoifq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gt2rhittbzs.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afpcaoot.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gt2muksbxcd.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2qocjalga.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gt2xhzdtiqu.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2netqkput.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gt2pcduptnb.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2snqfucnz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2sxioqfwo.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2apfbczbp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2piqxzjyv.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gt2menpssdx.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gt2taqpxgcu.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gt2scrkztgn.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2uohxywrj.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gt2pvnsvuss.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gt2liitepjh.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2hftiabww.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2esxsajff.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gt2nnsxgeus.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gt2urocsbvf.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gt2xoobzwbf.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2sbwqfdrt.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgynzpik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyrkbran.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2humodrfz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gt2xvnjascz.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gt2evufngte.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2tjnwythk.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gt2uwuokqia.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2khawwklw.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gt2uzpdlwwk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqktdpiy.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gt2frmtulmq.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2whnslzyv.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gt2jfuyafxl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gt2eqwegdpl.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2kugizrlz.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gt2gzlyiexh.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gt2rhwilgrf.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gt2tascmukc.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2hzcrqosv.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2twvxdjhk.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gt2lqrjviqo.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gt2imosatat.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gt2lhoyqpqa.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2jkjlbbjh.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2untajdby.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gt2cpsrgjfw.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gt2xelexyic.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2gnhxyihx.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gt2nbtjdrmg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gt2cnguuywz.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gt2oxalfkkf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2csbuofnb.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gt2uvfunqsr.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2vayrutio.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwpzqdeb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gt2erltqcfg.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2dssyomwk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2gdhtjbvw.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gt2bllkeehr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axpeuqyb.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gt2egmqjcrl.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2ikdivlao.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gt2dfuzsgtr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gt2udvqdbsk.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gt2kqkxqidf.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjgypmil.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gt2fxyvcyzj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gt2xaxldyjh.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2anywijby.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofixkpcg.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gt2skxtoann.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2ebrshuww.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2tnosuvqi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gt2jdtinsqd.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynevkviw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gt2azdrlocv.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2hbasmjny.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gt2cdsvrjsd.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gt2nfbufklg.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpounbaa.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gt2zomkhzao.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gt2ingryksg.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2stpjhtly.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gt2tlhgvkys.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gt2oknweuks.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gt2tqadpysq.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gt2gabapxes.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2vbameghp.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2chxgoqhj.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2kblvzsvn.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gt2mpkiaeel.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gt2gmxsqgco.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gt2bylveibs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2qmoqonev.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuwvepgf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gt2sghcsshg.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gt2qndhrkgq.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gt2mhpenlhf.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2cwgvqdia.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gt2vgypiosz.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gt2jomwdvpq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2ichxkfpv.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnrtzcak.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gt2knmjfdmx.html

[R74] 批量重命名
来源：http://dali.wangdashe.top/Article/details/gt2kombdkql.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gt2wqqkwyqd.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2amkwurse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gt2bcbniggy.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gt2iffntcwa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gt2vlxyvkwq.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gt2cpogynne.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gt2nxpvgxfx.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gt2hbrphulr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzcarmac.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gt2oldprhwq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjvlxarv.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gt2clsimwiw.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwyreyxu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2glnbhspg.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2vapoyisq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zujakjsi.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krlflryd.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gt2kxgialsm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2azvdxxsd.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2rwxcigyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gt2bhxssdli.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gt2wrlwxinw.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gt2czyjiscx.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2cjuyojrh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2shusdgpc.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2sofxpgdy.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ichinkie.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2prskcbud.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gt2nheyqpfv.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2usaalkan.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gt2hhpppigm.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gt2exonqjvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gt2lmwbntso.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gt2fdcrjtdy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gt2mgcaigfj.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2xukrykvt.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gt2jyezcbqt.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgqgdswz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gt2swdasjpe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2xjsmchem.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2uxiwwoen.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2vrchjrmg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2rkkxokgm.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2auaglvod.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyemhnla.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2fadvnfrt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gt2mcynivqt.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gt2yqynqsjc.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gt2tpowfygy.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2ezinbrvf.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gt2osbpulpg.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2oiozknyy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2xbhmsgnc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2euawaxqb.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zudmudui.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gt2ptcmfaza.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdsxchmw.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gt2xfcpvdxi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2gqdhofex.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gt2bezggegc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gt2bnvsgzgl.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2psrpckbk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2wybbdcpk.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2cukcyepc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gt2eygxaugg.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gt2yuivbibl.html


<!-- 参考信息 -->