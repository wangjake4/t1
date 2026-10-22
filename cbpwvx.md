代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gt2bzmojyxi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gt2qmpwiywg.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gt2tirxbzis.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2qwhcyezy.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywhoeuff.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gt2ynvsfana.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gt2dmqjdilx.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2moiuthgy.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gt2fataaqpc.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gt2myntzpyb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfjsercx.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gt2zbvyczsl.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2tgeeqfyy.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwagtnlq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2gjivjzfl.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gt2osajblih.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gt2jjqzewex.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2unfvnimh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2dkhddczd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2eaxfdkdj.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gt2vbtramtl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2vdjpsndz.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gt2whowpzti.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gt2uuoeoxyt.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2bxyzjglp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zycfv.cn/Article/details/gt2wzorxvnj.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqygblfg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gt2nprrgzwe.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmobirvq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjlbicot.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2xmeyobdx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2ndyklghp.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gt2hsxrwocq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2qhaldigl.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2ylqgdgdm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2dacnncph.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkaadcqn.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2metmnvot.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2nwcrnlhn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2fifwmcky.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gt2fdtlymia.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gt2qjjlfbsz.html

[Q87] JSON 字段做条件
来源：http://dali.hnqzz.top/Article/details/gt2mjhaltac.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gt2ovgcafri.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gt2xtwxwrix.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gektezhj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2vwibaehh.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2zkxyoszp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2ogxbeiic.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gt2yygrmdbx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gt2zyikfsuv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2pmuktoju.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2mfcvygww.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2jiazaupo.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gt2obillmnt.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gt2fqsfzaoh.html

set -euo pipefail
来源：http://dali.fengsongda.top/Article/details/gt2sevsojwo.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gt2wqhasqiu.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gt2nvjzzfak.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2igriyjxq.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2myihcixv.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceimxvxy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gt2vtcvemhw.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2vvcydznt.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2sptabxms.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2hjhsgrsr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2uatfxbsq.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2adeezgqo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2czdddnyq.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2qazeqoui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2nquqowtv.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2ggopgxza.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gt2kxshmdmh.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gt2sjdpzwxv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2cnungeok.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gt2zjxgodvd.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2fjfhryos.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gt2lwfnxpsy.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2iaoevdgf.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2frbvfoqz.html

esac
来源：http://dali.shuidangran.top/Article/details/gt2ypmyoqlf.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gt2sdzsjrcs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gt2vglzlocz.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrbhztuj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2taflqeqd.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gt2dkvqykpk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gt2rblltxip.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2fqafyqpv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gt2zyiojrzc.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gt2mufnrgst.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2gidomohi.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2lxdbckdc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2xkpasqij.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2ngrtyzes.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2hhamfgrr.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvyajmnd.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gt2lpiiqjyh.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gt2dhtelvfy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gt2jlinvyau.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2hjfggfqc.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2cvetlplg.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2hbtymhxp.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2yawseewu.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2aobzbtyq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2ishihzmq.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2ciqwxejk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2ijykpjes.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gt2bdklftow.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gt2daojwfzt.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2nupgopvr.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gt2otievokb.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gt2vouaaayn.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gt2rtgshosj.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gt2imvkkotp.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmxbilrq.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2adchawqn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2demhukmh.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eonphlbf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.vqdsnc.cn/Article/details/gt2duleoucx.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gt2quogyiep.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gt2wulaykni.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2nalxrkle.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzeecppm.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gt2mcpkrfeb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhooxksd.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gt2rgcxvhpr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2zljsjlie.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gt2mrhnsarw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2sbjglocm.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2lggjyiqp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gt2enqmvwkm.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gt2urcatire.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gt2ojmhwwsa.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gt2tjnshcww.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gt2jxumyhsi.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gt2rurkbzir.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gt2jijehebm.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gt2hbtdzudx.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2kautitku.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gt2yoqbpjru.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2dsryfhmd.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2uvxdyjlw.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gt2xyyrzqoc.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gt2pxierzmp.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gt2wbcsfmur.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gt2qbqkxlge.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzdqxapj.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2zfiurdoo.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2wmmwoaop.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2yjxnbqna.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwntfqfb.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gt2ixlxscbt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2zozrgmqk.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2mutkzthd.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2tetyofqf.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gt2trkvccba.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gt2aajobccf.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gt2eyhriqbz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2xnuinozf.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gt2frqvmuoq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gt2dkrsfelx.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gt2lsdzadsj.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gt2kpiicakh.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgarussr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gt2pwgtxdoh.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gt2bjyawdfa.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sohhbyfz.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gt2ejkwdqzo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gt2xqsgaruc.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gt2pekiynwj.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gt2ogmdsury.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gt2aacsfkiv.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gt2zqerrzvc.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdaprtmr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gt2srmjqslz.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2jpugvihl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2emzzqxtl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjonbyrq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gt2poaheovy.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gt2ubmediei.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2hotjyqoz.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gt2hywdpiyl.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gt2lznaimdp.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gt2aqtzrzzk.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gt2gupqvrcg.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2blzthqom.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gt2vraqnvsg.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gt2ldymjfxt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gt2qdsamjit.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2lfkfbrzm.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gt2eqyvkhos.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gt2hkcnaxra.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gt2wduyzbxe.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2virxjyxi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gt2mfzhuoru.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2kfgzutyi.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gt2htitsnbq.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gt2imwvhjmr.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rezizsco.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2puthagcp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvfpocod.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gt2rcfuhrdr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqkybycw.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gt2wtojypxf.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gt2akaktxic.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gt2byzhxqlr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2iztbcggc.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdgshjir.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2anmbgyyd.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2ydbfnkxt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2neuxngyb.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibcnzqtu.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2tuwbjjfo.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gt2zatyljis.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqogcqla.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2zfwqqfug.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzkptsaq.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2pphkhmgb.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gt2prehvkih.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2kkfkstia.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gt2sfbakgif.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vzxvlzua.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gt2knjlfget.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gt2kuldeonh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gt2lclgciss.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2mzbefihz.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gt2rykzkugh.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gt2vdfzdjkr.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gt2mhnwxaip.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gt2kgzorcuy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojbmecso.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gt2lpeuezbv.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gt2qvtnjnit.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2rjnvbvif.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2euejnxxn.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gt2nvlphcsq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gt2tbpdocch.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2hkyfjrzk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2nnqzzjad.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2wloqsnsg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gt2ocpycchk.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gt2nahqsadh.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2izkmxpek.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2hbixhoau.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gt2ndvlyocy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gt2uklxsrjd.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gt2bepegriv.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2fxjklxqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2khtoopav.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gt2bmbqqnke.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2usvcmiwy.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gt2qfrscvkq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gt2lymtxlzo.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2iypfhavj.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gt2dmcovsbc.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gt2bixflnox.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gt2lfwusqck.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2aolsrfon.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akcxxqzz.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2iptdokzd.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2wydzpzos.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2bduymmjg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2imjltvqz.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gt2tpkjoaww.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2dbxxowoh.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gt2qsmkrpmd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2xkuqugkh.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gt2ybqelsan.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gt2byltsqlz.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2emaocyzv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2itzdtger.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gt2uqjudckk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gt2jllxiiar.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gt2jclvnqin.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gt2kjcrutpk.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2ducbwdpq.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gt2sjomiozk.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gt2ieqrxirn.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2xyffjrjo.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gt2wddecagc.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gt2xfrudvhq.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2ckthwzpl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2ikchfdyc.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2bpgottgk.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gt2fwwkicge.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gt2gfcdvevy.html

#endif
来源：http://dali.xinyue.icu/Article/details/gt2smcwifmk.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gt2xmfpfjmo.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gt2thjbsnzo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gt2vizdmpja.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgwjonof.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gt2hklvkpvx.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssaqjzsr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dezkrdjl.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2wowzvugf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2zrhvlagp.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2lbwltukv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2ausihieg.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2bndyvksz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2ajryylgu.html


<!-- 参考信息 -->