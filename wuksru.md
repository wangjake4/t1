代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gt2yfujixif.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gt2keovwdvw.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gt2xakiqdyu.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gt2sbpomfxs.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuscnjhh.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gt2afsazvpd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gt2flthgbpv.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gt2lmhntqun.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gt2mbtxyojx.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gt2cbirgaug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gt2wqlfewop.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gt2yvfdxajx.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2cparrmjr.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gt2umuqchjh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2ipvkymps.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gt2udgcfoba.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gt2yecmjpib.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvxyzkwc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2taetrlui.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gt2uumalvbs.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gt2oydhwarl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxgapwqw.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2rceriink.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gt2usyflyxi.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gt2evudtmsq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gt2mylmcwiu.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucmnvtmc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gt2hhtlvekm.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gt2fnyihstb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2whtipxdg.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2zkbbjkfe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2xhqpdyip.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gt2cxohdhcf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2pksqhkwi.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2dhpqfyoh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2wynqdbat.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gt2qzcrddio.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2mgkoxnbe.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gt2owwelrce.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjxxwsqu.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gt2elpeuwfu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2ulbkmftj.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gt2oluvxyfq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gt2fvamqohq.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gt2qwlukmqv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2lovyldrb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2rzerocio.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2wigpfegz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2ausxzyde.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gt2hsxtykpx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvulvzok.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jsxdpjyr.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gt2wsflxgvt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ueysjqpe.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gt2oneienjj.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gt2ssidpwom.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gt2zmkyxwqs.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhnoyerx.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gt2rmpcemxx.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gt2yjokarvd.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gt2mcgoxdfi.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gt2czzmdkek.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gt2mambjynp.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gt2hzyvdjjb.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmgcwaia.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gt2ddblomcq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2irnyvbvz.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gt2rgjyfnhn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2auswgvhu.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gt2dypxajlo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqhdhfet.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2qyvlrwyu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2yycesnak.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gt2lantdbak.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gt2duqravdo.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gt2dtagpttf.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2uasyyhpm.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2oksbggkv.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gt2jftkqgxv.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2uitxgega.html

esac
来源：http://dali.wangdashe.top/Article/details/gt2rwbhyena.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gt2xvtvkkib.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuwjjkyl.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gt2xlwdxlzw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tedjjmft.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2wkcqejho.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhtuuyj.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2jgtbnqae.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gt2flsflhix.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gt2rqvmrqlx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2vngorhhr.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxvwwtvu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gt2cponxidp.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gt2bybodkbo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gt2rcktbavr.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2qfbmitxz.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2qttwnskj.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gt2setahdng.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2ngnvqzfa.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2ztbhtnuk.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2lhmsjatp.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2wdbyrecn.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gt2pvifqfif.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gt2ohhmvxpi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gt2yjbgwrbe.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2jzgedlsk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2xmhnhkts.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jizlncft.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gt2criyvapb.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gt2cysnrhqu.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gt2mlxvxlrm.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gt2dfuhpprr.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gt2wfwnpnqx.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gt2hzgjgjoj.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gt2hdwqfoyt.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2zyokyvjh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gt2tzuzpneh.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gt2qjnsjmgx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gt2sutxcedi.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2ioekimly.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2ilwyxwia.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gt2ietjsxpa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2dwwpctrf.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2zuivxung.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdrcbzsm.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgctsbxx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2aakdilwp.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2gvrtrhgu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2gvyxzndp.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gt2gayugviw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gt2ezdvygdx.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gt2lqrnkpks.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2clskvnlw.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xihldhct.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyawefsl.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2ciwtatxw.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnfewgfp.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gt2lbolmtyo.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpsikjen.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqiglpdp.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gt2zzhwszmd.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gt2xsdnhnnz.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gt2irihnuws.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gt2bpltvzdj.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2kdlibtyx.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2nwyjjtiv.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gt2sznzkjvo.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gt2ucpkvgtq.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258.top/Article/details/gt2uewssalj.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gt2eailzeqm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2yftbvsvc.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gt2mwtlvajf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2dttuypyp.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gt2mvoofjga.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2sjoybbfg.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gt2nyhhrtiu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gt2lcmtlgaf.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gt2jvyjsuog.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2wljrtfpe.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gt2mpkdndjh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgcverzj.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gt2rfuudpar.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljzrsuoz.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2xuxqpuka.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2nvsjxnyp.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gt2sfyqnlpe.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gt2yfpdsjrv.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gt2wwukryoa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gt2mmkfgxiq.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gt2yyiecfba.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouzfitez.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gt2cgxlccrr.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gt2mtwxdyej.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2odyvruym.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xihmpvmu.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gt2juvvipkf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gt2ttdvwbgz.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2jbfscvrc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2teuzdaet.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gt2kayokwyo.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gt2xswkvdnm.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gt2ybthxwpl.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2ibbkogsy.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2vnggdcta.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gt2mulmzkss.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfzabwdf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2zzsdwevc.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gt2jstjemjm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gt2fzrzzjgg.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gt2ztumeixj.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2xzeigawk.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gt2fbhytcoe.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gt2fnssbzts.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2lkjsdgea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2ohuzmljs.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2tspdaoub.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2ksskpzvc.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2frlqxqbc.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2qdxwvanu.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2vuzphdqd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gt2pzpxbmok.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gt2ziokjiov.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gt2vnaoewyi.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gt2hwpuaeht.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gt2cfhrtvyv.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gt2vqokhruh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2nvnrcoxx.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gt2rzswqcnf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egvahljg.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gt2qlnjjqrm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2gsdhnjkg.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqatdsux.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gt2uucbckia.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2awnsriqx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2ywxxqmxk.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqakmkbu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gt2cyhdkfhl.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gt2wfhrossj.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gt2iyxmchfp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kyfnhadg.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gt2twvsnnqj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2scmeqkek.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gt2bizqhocw.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gt2dqcfalnx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2snzkvagh.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2mquagdtu.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gt2frjwceql.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2tgqchffo.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gt2fjjkntel.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyottqey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2inhahhcy.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2krifldfr.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2jngbsqon.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2ggoulvsg.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gt2fbabmyaj.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2htrwpcwr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gt2utmcdpqv.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gt2cqevokco.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gt2laeesjqx.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gt2uuedhlty.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gt2teqbjffq.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gt2zpkanvfb.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gt2dzjblagr.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2octmdgsc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gt2zyysayng.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2knbkejyp.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2amqyjcmu.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gt2zorvtirn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gt2mnmzfowp.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2frzqyxdv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohpmrvsf.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gt2aliksfeh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gt2lqgjgwxk.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwbilzaz.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2iwjkbhwt.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wioothdl.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2kqlomqzs.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2bqzslxuf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gt2syzflffe.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gt2hcecjtul.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2psmsowpe.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gt2zqptjzgx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2swntvqns.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2rmixuxjc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2frbahitu.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2odsobngy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gt2hguxsqsj.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2btamxret.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2bznzguww.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gt2vsdcksvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjpgodiy.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gt2qsffxmfd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gt2mibrgylr.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gt2nfjouvhj.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gt2kkpzijdi.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxoekpgk.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gt2vdyiyard.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gt2tzavltge.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2sebsjyxd.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2lsmdlrgv.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2fkeyybsh.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gt2alsajltl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2vjhawdxo.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gt2utkbbuxg.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2ygtuyvlu.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gt2kfoovoox.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2eohhysyh.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2ckpsfaas.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gt2ixxappjf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gt2laxnqbxk.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfynvffi.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofwnihcg.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2wgvayxcm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gt2ppkwkpxy.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gt2uidiaczf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2cmyettom.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gt2jdsjmvsg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2wulctqll.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gt2dhaevetr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2pjsjkqnu.html


<!-- 参考信息 -->