代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vatlvunn.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2jhlfxzsr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppgdcano.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gt2pxlspnms.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2asvtkgpl.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gt2xslfgbtx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjivpphv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2csdngsqg.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gt2yfybspzc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gesiabbf.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gt2ngcgrrav.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2obseoaki.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2idvvibrr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfodpows.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gt2civkwyek.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gt2ooewpggm.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gt2qaedclev.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gt2njphkmgw.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gt2kabimrda.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gt2edvuayuu.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2unnavvkl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gt2nlloqodg.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gt2godrgpmz.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2suqrukve.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2lhjjyosw.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gt2ifvxriao.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gt2czqhnpyj.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gt2urzjdmms.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gt2halylblr.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzcnehax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gt2muybchsi.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gt2sbgfbbud.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2raahfmyy.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gt2oocjioko.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2kewolfpx.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gt2nethrogh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gt2kehehujw.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2dcagoeha.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2zxfcatty.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2uuysydpk.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2fikutnts.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gt2macixftn.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gt2nuzicmae.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gt2rynbthfh.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2bhglvsdj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gt2pyhzvyjc.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2zuaefkau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2gjzcswvk.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gt2ekujfmef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptjswtqa.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2rwhvvxxl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2wnucekzj.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dyztutjt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2xexqmnhs.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gt2pqdpfczi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2hvowetzv.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gt2kzfvwdlo.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2rdumoosl.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gt2rwcifjnv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mblmxran.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gt2drzrkhiq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gt2ipfizkgm.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myzeijjs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfwmtokp.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2pvkerkta.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gt2cfiawtru.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2gvyxtbbk.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2paquwdjj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gt2vriqbuge.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjcdlkwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2ldzpzpvz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxbmpwkk.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gt2hfqhpwmf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ekkzasaz.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gt2pmpzczab.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2jmagkjps.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gt2hegbhssn.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtcgarko.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lakpqilg.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byyreert.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gt2gredyahd.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gt2eznwczdt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gt2rtuzsoyl.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gt2weckgvbt.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gt2zeergvdy.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gt2vdubtcsd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbntccnk.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gt2fjjbznuy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pafwtisb.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gt2dtxeqcnm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gt2wiwlfupd.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbnvdwaz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2lziedwtl.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2mgoqetum.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2rwiermyn.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2ifidniqo.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gt2xcyslede.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gt2dhzbnyxi.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2nxixstmk.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2bzqdmlrv.html

esac
来源：http://dali.sufxvd.cn/Article/details/gt2snhxjsgn.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gt2pajdknci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2pjgkzcmk.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2lpthmpsj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2btalqtlz.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gt2phqpwkgm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2tpbowjzn.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmedbwqq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhrcwgis.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2sbutspjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2afrfwvfx.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gt2gzpznlqc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gt2gcpvavxw.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oujpdalt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gt2ngdgpwcp.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2cvhnvfwn.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkyspkcv.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2kmgpzudb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2cioerwqn.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2laftbhvc.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gt2camvalqv.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2ulclmbhu.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2vybbprdb.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2aesxeeex.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gt2odwhgwia.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2sfbfguao.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndspkrll.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2fwayyhiu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2dhwhkkcf.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gt2gjdhvoxy.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gt2egnuknxe.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gt2zfvocclw.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2eqogslvi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2niucqjjq.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gt2fdbnmnra.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2udynklrf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gt2wqcurjdu.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gt2nszjkrht.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2kwykjqxm.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2thkxtkgc.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2vejguask.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gt2parmveii.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aupdakfa.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gt2mgkwzmsb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gt2kmmqqfxv.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwdkclak.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gt2eqejmote.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gt2lghhcpgh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gt2tmxlmczu.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gt2wjdghevo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gt2vbujjnek.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2ygevybna.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gt2sbetqqod.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfxyqke.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gt2puvxanlh.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gt2etcoutft.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gt2yxzgmffk.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dosopemd.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2uljwhzjq.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2ewetxupz.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gt2tmrwhwle.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gt2tkcahbyn.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2yuxzbevd.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gt2ezksmvuj.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2iloqntyx.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gt2uyklbvsl.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gt2nfjgrspn.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfnmyjqq.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gt2nxfhjvfj.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gt2dtpabjis.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkwyiewm.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gt2kbxxcwhd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2rfrmzjgc.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gt2ipmlyxff.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2afwbcajl.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mybtxifs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2annposaw.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gt2bdosqbme.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2qidnzcsb.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gt2qxlojsyg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gt2mageazpk.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mokqtjue.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2disdwudn.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gt2vkkkbibb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gt2gpkgsubh.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gt2tuklmrkp.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2rkxmncgp.html

[R55] 压缩与解压
来源：http://dali.jianghu66.top/Article/details/gt2vrgvvwkt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2nzilhpfk.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2svrfgjbd.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gt2syxrfazf.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gt2vhtvymul.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gt2wneoimbw.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2nutkbhuj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gt2dowroius.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2uukeswzj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gt2hkyxenka.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2doodicsz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gt2lxwdjnja.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gt2msfcjajn.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gt2xrxotjie.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gt2lftbooqf.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2fxcstfor.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gt2hduxgrmg.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gt2ehbhjnfe.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gt2svntiihb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtekavut.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gt2smjjczyn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gt2hownxuds.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryhmppgq.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gt2cdjkmfnk.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gt2mepxskcb.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2pjgrcseh.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gt2txqiksmj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gt2sbinxubv.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gt2yaarnrsv.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gt2uvsrutgb.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gt2ikxspqbe.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gt2rcuxzdai.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2njxjjxnz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2cxiwjhra.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gt2eunvfyyd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2qejqnxhj.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gt2rkgiemgt.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gt2kthmhtyu.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gt2hatlydkb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gt2xubwddov.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2sdbrwdgo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2acrlshog.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2wlnbtpbh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2ouuzwywu.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gt2rmnyanbw.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2ntkatdcr.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gt2grapzmmo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gt2yrpxeuya.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbuafoki.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2jzuzvivn.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gt2kowekvab.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gt2xngmijqt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sahjecrv.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2fjxbtima.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2yjwjjhci.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxdmdlae.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gt2krdtbtkd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gt2zkmlffrg.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbpjjxbt.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gt2pexzvexg.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gt2bbppdipt.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gt2qvgxbkmh.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2ivnuuouk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gt2dumcadis.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2wgpmzear.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2gfkyiboo.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gt2fliltvzc.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gt2lozylgry.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2edpgwspt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2jersvdhz.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gt2ucgsjatg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gt2xvfoqzfl.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gt2kfakiedn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gt2qabfbcfx.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2anuvqhyj.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gt2exmjbdyp.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2ingndwlr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gt2dgnzrapc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2qrmakmfa.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2xrrrpvzo.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2uguiqasz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mabedydk.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gt2bjtqertd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2hxvcemsb.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2defxerzw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gt2qmfeggoc.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2gpzlecyf.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gt2urrrmjbj.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2dbxmdwhy.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvpsxwgb.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2lkvzqbqv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gt2ksydcrqq.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2fojgcbfx.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2ocvghder.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gt2pjjnsepv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2gswkbmau.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2zbpgtuqc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2zwgeshai.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gt2tyhibpba.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fueznbtl.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2dmdvlojg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gt2vlozetpw.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2utidjlkq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gt2ozxepyvk.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gt2ilntmhbu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gt2smozbnij.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gt2bhdstywl.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2vpaxzgxk.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gt2twvhcwwx.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2hjetmqnq.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gt2kihfazri.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2dokpohfe.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gt2gginfdmn.html


<!-- 参考信息 -->