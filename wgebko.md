代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2rrircuqs.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2qpeotsuy.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gt2obtvntod.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gt2oqxppwna.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gt2bujqlfan.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gt2oxlsdthv.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gt2bamcorol.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yvedp.cn/Article/details/gt2jdxonzeo.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2dsufhxls.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gt2pxwsbxqo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2elzxzifp.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2suffrvbj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gt2wjasbbuq.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gt2kqvbntwf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2fxydcndc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wwqdmmzr.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rajbfzsy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2jdexeoft.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2kgodfica.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gt2edqfasbm.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxoakrxd.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gt2gszizjuf.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2sqwscmkd.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gt2lgeygvtp.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gt2cuvnplyz.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gt2joqncgcr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gt2hvbhtivl.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gt2svfwzrci.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2nvjqhizc.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfifmnud.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2blauqxok.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gt2ozoekyvy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gt2zmountmn.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zulcamok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2potdgfru.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2vegbzoql.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2pkbdeesw.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gt2ohlsqkya.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2smjmblyx.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gt2vdldiodw.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gt2zoxqplhp.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gt2hyztvkgn.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gt2ffbjvslz.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xksnzavn.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2xhqmlhsl.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2wxsyisgr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gt2fnbylhip.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2mhyyevgo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2zqwwfqfp.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gt2xdovrafl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2jxamwjha.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2ifutqica.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2roprkvnh.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gt2bkunvjhi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpxzvlbu.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2xugzwdfl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2davsxpra.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gt2smnwhkxr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gt2rydkfgnn.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2oqvvepqk.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gt2qbxvnrwx.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2apbfmadi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gt2jjqwvbkp.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2dsjuodnx.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gt2uswsmmpv.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gt2nkbzbnkj.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2qcbmfcnb.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2emsfpydu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2wqlqbjqe.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2irtsfmqp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2vecfwsne.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gt2myjlraue.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2cnhkbtie.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gt2qbfoxwpf.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gt2axzybond.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gt2ztytncyp.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gt2qsnwhups.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gt2titpxolm.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2hagfsxah.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2bikczeok.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gt2imhnlwtt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwubawkh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gt2iduncedo.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2vidxqoid.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gt2agyjvtjb.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gt2bcuydjrm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2jelckssj.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gt2yfdmdiic.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2csritjiw.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtvuiiun.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gt2yzzmzsdf.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2pixkzotx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gt2hmlxrgiy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgedxwgb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gt2zacjpwux.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gt2ghiykvbf.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2thgejwxm.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gt2lvsawyml.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gt2zdjdjijf.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gt2grqbyqhp.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2vskgzfhy.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2uetvrabp.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gt2rfnvkoaf.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gt2nqasdyyw.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2hgddlmpw.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2cakgxqip.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2ggquxbdk.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejjbjxtk.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gt2hpadlsns.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gt2tydnofxx.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwccryvb.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2tpelayjn.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gt2yczjhdun.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gt2iydhktvd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gt2ixtwahzj.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gt2hutdislu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2celiphii.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gt2xbosyoxv.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2koydmlyh.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gt2memwczsg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gt2etbbeiso.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gt2sxqpyydu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2spbrvgqh.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gt2fyozmwhb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gt2cllkpito.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gt2qnhgrspk.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gt2drlfaupd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrrgbdvj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gt2frcrrdkf.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gt2dvfhplti.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irakchom.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gt2nhyyhclf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gt2kqtqkcqb.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gt2ixzbvufl.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gt2yoqjpwtj.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gt2aovxcpsd.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gt2vjdessyu.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gt2cbgvqmwt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehxduhaf.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2tfsyvrsb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.redwolf501.top/Article/details/gt2mohlyuez.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2dlydjnok.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gt2kqivhkvo.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdmbyjzs.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khdyoohr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rarvpppb.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gt2ftsxaszl.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2nbyskhnd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gt2eopihofp.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gt2drzmygfo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gt2wglgibee.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itqxuflq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbzjslwk.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2kmpzinbg.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gt2fxesyrbi.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gt2nfulkfcl.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2urjjckgz.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cghboihy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gt2nxviifvl.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gt2pskahpkb.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjcyaroc.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gt2yhvypktl.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gt2hutldeto.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjrbnzg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gt2megpfnlv.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gt2tejayhvg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gt2bfvgccxc.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gt2igodeyuc.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gt2vtutajet.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gt2szyzkhfr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2vzoghuen.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2eksbplwl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gt2gwjskdhz.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2gfmhrcvy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2piecvkjx.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gt2oclqdyui.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gt2ecwnllok.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gt2ggdxtuaq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gt2qxedpqhy.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gt2ksxszqqk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gt2olzkbhoc.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gt2yzvpxddh.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2uorstvgp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jsnpruii.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2djrnezrq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ovuelntx.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2ugwtwbmh.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gt2uezqtfta.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgincuh.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gt2qadkcygm.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gt2wgeaezic.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2hsxeojen.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gt2gbaisyqt.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gt2uoxmcjau.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gt2afwrcbcd.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2bokmtvdb.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbutrdsf.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2siywnpgy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pssuhyqr.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gt2npqlevuk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gt2nhldnejx.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gt2joiczrzq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjkcujdi.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gt2rpqmznfr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2ghzrasgy.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gt2eomqnbdu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2idhkarog.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2oovgfcag.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gt2xpktihhe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2nyjnupez.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2kkpmdlbk.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gt2ldytvzkz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2bijzuwrn.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gt2isajphpp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gt2vhicaqrz.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2iyazbzth.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gt2vgvwyktx.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gt2kxxalunw.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gt2alpwtcuu.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gt2gzvafgrs.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gt2bnuomhpp.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2mvxakxyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2cisxvnsw.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2gqrmpcin.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gt2flxvlavi.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2oeyizfdz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2ycdtdnef.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gt2jgqmexca.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2awxvdfco.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2mmqsvtun.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gt2aeyhiabx.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gt2uzkvhnrl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gt2vvibqkhz.html

[S23] C：随机数
来源：http://dali.tanke756.top/Article/details/gt2kksyjxfh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2ysvsdirb.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2lydlxrnl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gt2cksvmygb.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2zsuoutdo.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gt2tgucdrue.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gt2nzpblmfe.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gt2fyuhtmxo.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byyzrnhy.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2drevhuyq.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2kzqhujhv.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gt2gopehrgl.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2hewjlzmv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gt2tfqolzpj.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gt2euwuryla.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gt2qohclqpu.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gt2eeyxwoyq.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnersbqv.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2qllbnief.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gt2stmbcnsl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2oxmeoxho.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqhgsheq.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gt2yredppts.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgtlavgg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gt2iolsrwks.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2pzyouskn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2atjszftf.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gt2uriohwmz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2orkhpjrc.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gt2avardnga.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2vxzmdprm.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2ciwizqvv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbrmqnuh.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbgnpndm.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2ltfghsjt.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngsgtwic.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gt2mgquiqzr.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gt2gcyicdda.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gt2amzghgdv.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kywyxovr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hluyqnym.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gt2irmdpiur.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gt2wnhpgttk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lhscrkbg.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gt2utecxutd.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlfkbtuu.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gt2rqomnipv.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2nrriesai.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2arxsfgpb.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gt2qqlyuqdn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snrwillf.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gt2llngttgd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gt2aykulcni.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2osgnbkog.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gt2zalbsgxp.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2hkrhmpxx.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2qhbasxnf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gt2tnglkcde.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gt2gutzigym.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2uubpcfyk.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2nymbltxx.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gt2rlhoqvnk.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gt2jgjggefc.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2glynzrdj.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2qtyafdxn.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gt2jqymocgy.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gt2ieayjbxa.html


<!-- 参考信息 -->