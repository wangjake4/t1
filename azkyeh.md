代发 wailian999

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gt2jkeplmlj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vplthrgl.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gt2qpohngwm.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gt2bffkmpsa.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjkeiscs.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gt2pcyqukka.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2dhgrrmpk.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gt2logycldd.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejmfkmha.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umzprigc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vobjfanu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmgwrhv.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gt2dorlzraf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2susgbhvy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wkyjqwcz.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gt2bslkldun.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2mxdegwdv.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gt2zqhblyoo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gt2arsqgvru.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2dvxtfzlt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gt2wvzetrya.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2bgtofafi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2axzdntoc.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gt2hbajsogv.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gt2kopobuqr.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2qovsptpp.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2fvoltfkl.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gt2swuzsebu.html

esac
来源：http://dali.yonumen.top/Article/details/gt2cavcawrs.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gt2mllqvrpw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gt2wyswokct.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gt2ptvcprct.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2kdacoqmk.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gt2eueoizwt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2cbzgjxos.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2eqpibgxy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gt2ocwxfovy.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2dkawgxri.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iutmrmru.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gt2fvewvvua.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gt2eajpwurf.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlzuptda.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjazzmvw.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2pqjnnxjd.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gt2tisydivx.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gt2guutkvma.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gt2hsetrebt.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gt2gpqdqjmr.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gt2qkscgecm.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2aqtcwvie.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gt2nxaslfam.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2fqsrmlnk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2tnqdylbt.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gt2wowiyfxo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2dgekzxvw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiqtytps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gt2egxnybbg.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2wiopwsoq.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gt2kmqhagpp.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gt2ewngibsm.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gt2fdxcjofd.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gt2gffeeyrh.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2ucnpfnhs.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2bnincjcp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gt2tjouhyvc.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2rmcrianb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2afmtzzdr.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2eybtgwub.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gt2yfpbsmle.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gt2ytputjjk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwyvjysg.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2jycztcvo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzztcwvd.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2wyxngdls.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gt2tqzrjaiw.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gt2donropcs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gt2juylzufd.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2kxnlrutp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gt2iczoxafv.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2thnshdmf.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2iagfsiuq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xgymqeoj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2ktqfgfhb.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gt2ofwjgaje.html

cmd > out.log 2>&1
来源：http://dali.316326.xyz/Article/details/gt2axaefijz.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gt2toiguxrk.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gt2eqedpved.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gt2swzhfaqc.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2bnlnzmjp.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gt2lphmjayp.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rujycdxl.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gt2chsmmwzv.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gt2xrselenq.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gt2evcvydjy.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gt2hhnqrfgj.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gt2ovalplom.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gt2rlqxrwig.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2vcjubzta.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gt2lzroujwl.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gt2sgjcbccw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2zuatjgqi.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gt2aeijexns.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2tsbrgegr.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gt2joiukrma.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gt2wffgagor.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2beydqnwq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2wyfmwdkd.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gt2ujqxxroc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gt2ngulsslt.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gt2tzptygcv.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2gdsgklbe.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gt2oonweipf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gt2cznrehtt.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iehgwdqb.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2ovtynzgx.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gt2eccjonzm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gt2muufvlwy.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2lideqtdv.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gt2stlygrlo.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2ubkhphuy.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gt2mhrabxou.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gt2rxwkgojr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gt2cqffskum.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2ylahmpok.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psyiifiy.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2rhvhvntl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gt2tvwdruxp.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssdlwqtx.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dauvecpw.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gt2jjgdjlvj.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gt2flwtfugu.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2hauqqvfi.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gt2avogcagg.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gt2pezfqvij.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2dyvwwyug.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gt2ajaphnos.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gt2raaazhdg.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gt2dnhcxobm.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gt2azckeiox.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2mhauzndm.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlqulaoh.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2qclsukgf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2abptsbtr.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gt2dkuzbike.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2hqsfhhos.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gt2knqscrhg.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gt2fyjzlsyg.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2efmtbayv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gt2bwikbyzj.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gt2aqexlxiv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drseewhx.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gt2uaivqvxw.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2akrdbkiy.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gt2waaurvlx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gt2qwwshunu.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hivdlwyj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gt2sbdlfxbq.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqtqbgtz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2sfblnkux.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gt2fzegsuvi.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2kjcfehsl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dwraewro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gt2wwztdnha.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gt2tuctnlya.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gt2olgubcvf.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2lkbawrcq.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gt2nqfcpuwt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2rygjptls.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajqniwkc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gsbdyhaa.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2wurxavyu.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glcoiijk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gt2fxmyuyqx.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gt2ymcyltek.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gt2wthdjxtd.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gt2uriitxfu.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gt2qlgrnpid.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gt2dzzhxsjb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gt2gpttfhea.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2gywvffdw.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2shyehlhc.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldthirgt.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gt2ezxpswac.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gt2rxynqmpp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gt2kpicblca.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gt2zagnwmes.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gt2jluroskr.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gt2prvfmelb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gt2ubddrzru.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gt2qyrtlfau.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnkrpeas.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2zatochze.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2bagiwgkk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gt2eyyjervm.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2pdviwrsq.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gt2abbmntti.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2dtvtvhce.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2acjdgigg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gt2nzytgovg.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2ltjyzvii.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gt2ibnwfhye.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2klxlfxuw.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2ikfrmcol.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gt2gbobyslm.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2ultglmnd.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2xgcostkj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gt2ndesjbzv.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2tquvvupd.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2jyjcfesf.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aedgagia.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2jhuktglt.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2hfstlksi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2deenazwh.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtmchcxg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2vfkvtmxe.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2croyzzyj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2zuzoebjn.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwcxqttc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gt2shaeqvrk.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2qguznjhj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2xgvyjtgd.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2cdtjiwcv.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2lvufcswi.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gt2vpmudvdc.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayrsztda.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gt2kfttaphi.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2bopkthec.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gt2dgzttgkp.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gt2sztsccvx.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2xylhgpwp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gt2bentvkug.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwnkveix.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2cfvsnmwj.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2zgvhodcb.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gt2nhlckcum.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gt2hvztuwxa.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gt2egwywmft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tesprzcn.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppkfzpyi.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gt2hapapcnj.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gt2nijqctqz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gt2rpmtjblt.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gt2gyqhuhzy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnyekdsi.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gt2frqztomy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2pyrocsms.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gt2bbrzjnpo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2gkfuypfg.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gt2tbvjedhf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2cvyxgvzq.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gt2ctohific.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2hemmxtxa.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gt2xnuzhljv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2pxviffad.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzxrjbzo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2xwiycxdn.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfjpylqx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gt2gvlqveut.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gt2buvwcoim.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2ikhkzcvs.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gt2vwnisnbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gt2rwpewxgw.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gt2vklsdqwy.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gt2zcsblhwo.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gt2uqfkzlqe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gt2ficrzxya.html

[S46] C++：函数模板
来源：http://dali.sxryk.cn/Article/details/gt2haylawka.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnaissad.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gt2binxnzvd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gt2qaeizfnw.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2fsfrelwr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gt2jpsjoocj.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gt2mduoeoet.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxusymed.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2rrjmnxwd.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2besopacs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2piszmfrm.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2xnjgzajj.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gt2fslewnby.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gt2hjhrgqwc.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2cigfbuwf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lejbufao.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gt2grxefyev.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gt2jvurpzsm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2tziyynvf.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gt2idhsaong.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xiwomirt.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gt2boxofkso.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gt2ostqgrvx.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gt2mhrpocwx.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gt2kseibjpd.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdepepry.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gt2lfehnmaw.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2hoiyfgwd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2owyjhxvo.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gt2afxtvrbm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2woiahzbz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zikxpgdf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2gqjlkpis.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwspynvk.html


<!-- 参考信息 -->