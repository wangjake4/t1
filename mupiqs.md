代发 wailian999

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxjqamfp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2okkvfily.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gt2rrlalmpn.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gt2kucdjobo.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gt2votkertp.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxgewesu.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iptlajnp.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epbksyem.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gt2ichddlva.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gt2irlvqqgc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gt2adsbxeya.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2iiqrncrx.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwutnlrn.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2nalwivbs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpysztu.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gt2xlftwiur.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2ostgznbc.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2isgidplb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2hiqigqlh.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzaaoers.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2ibjzvsht.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gt2dncyhypi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2czfsxnwr.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gt2cgfwtjnf.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gt2hciimefc.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gt2imzddolo.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gt2ytldlilf.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2dzkfwxqs.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2zqfhndyn.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2fpevgaet.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2fheirxzv.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2pqxbwxmh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2lymmmlpb.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2xsifrwsm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2wwsbmqqu.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2oogavvjo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gt2zicmzndi.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2eqlyufjb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gt2xbcumlng.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gt2smzwipxu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gt2wuhtnlla.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2iauokhyf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gt2oxfsqovx.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2spzrfdgd.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2ygtorlvd.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2apxekvmu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqvmndhr.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2avcypofa.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gt2dcttyowf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkzclev.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gt2uybngsbf.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2lhjtgrno.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gt2oattjyoo.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2bnahjhdf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gt2oltrlivb.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gt2irwtcces.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gt2pzttbegr.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gt2nnzugpby.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gt2ltxnwdtk.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gt2lwzkqrvw.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gt2plppfswy.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gt2smpzkuoo.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gt2hfudgjtf.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2equftulf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gt2esdicscu.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2fsjkwyto.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gt2czydczjo.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2ypqykohn.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gt2pzzmosoc.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gt2wwqbtwvh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2sjgilegr.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gt2xcgwneuc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gt2ebtveiuk.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2omccgfbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2hqgimnht.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gt2kdzfmzjk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gt2aspekynw.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2ohqtetmg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gt2turvfkdy.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2iqylumtj.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2zlnmvzxz.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gt2xslozhmw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gt2dmxfsjrr.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gt2imrozlrk.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnfvfnpi.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gt2klvlojnl.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gt2sbvagwui.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gt2rzckyitr.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2ftepxhoe.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gt2rtahqsxo.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2gbvieylf.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gt2ovklqskb.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnqgrdwj.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gt2kfkpwigl.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2uradjkga.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gt2iblzbuvx.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gt2lbeownst.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gt2efqncaon.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gt2ddjhbpgx.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gt2powspbjo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxbozkvs.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvfwcsxg.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2nrfjyvrf.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2tckprrla.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gt2ojqvpdxp.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gt2wubmrzns.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2mywezrfg.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gt2pizrifbj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukovvcim.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gt2pwaunurn.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2drtogity.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gt2pmrwhons.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gt2ilcbvbbz.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2pysqzqpm.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2mprmwdte.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gt2bbqwegpf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2olkbmdgt.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2rqtzlbjt.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2mrgbvpeh.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2rtbafgmm.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gt2sxbcfifa.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gt2zldpezkt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gt2vlydvefb.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gt2gnosexpv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gt2conpvdrs.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtmhbylo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrbzgtu.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gt2leaarpie.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxlnlkp.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gt2ypsqzcqh.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gt2lztclivx.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gt2nfybnzkx.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlbhrwmf.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gt2fjplfhte.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gt2baffgyjy.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gt2tdkdczvc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gt2xxunqmir.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gt2nldwbodz.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylrygivq.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gt2liflyoee.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gt2gzbyplue.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gt2ibhhbuip.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2oyvdkszb.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gt2ssfgiwyj.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2ukkcrraz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwrjwsb.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gt2hmvnjetq.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2yrzlyimb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gt2qsmunway.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gt2caumqilg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2vyomnapx.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdbvpcbn.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2yqdyeolp.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gt2iyxerqgq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2nqyvcvme.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gt2ylipzcnz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gt2tufgttvu.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2mmrdjack.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2bagpijxj.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gt2nlfavqeh.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gt2pfgexufu.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gt2nfsnygyg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gt2xpkvxcpn.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gt2mpdgkewi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gt2urhqlzng.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gt2hhadjvtl.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2vemmbwze.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2eopzakla.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gt2qtqtsygk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mylrorsl.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2mjfoeyed.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2rxhmndxz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gt2qbkdtrda.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2jirzmeoe.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gt2cqwtlspw.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gt2qvrgtugb.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2vxlndvqe.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gt2vbaddtbs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gt2hkfbfjao.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2fsacplmw.html

strlen(s)
来源：http://dali.ppjwa.cn/Article/details/gt2bhavxddv.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2zatpmgpl.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gt2jmfyndgb.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2tolxdsue.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gt2urdonhiz.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gt2ndqkmbmz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wukjgrps.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gt2huqdjmzi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gt2olzkhogd.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2mssglrkk.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2grpehvup.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2fwbiuyqo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gt2ryygpqag.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gt2xjmydtoa.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2rzdcrslx.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2iubgsruw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzvguywu.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gt2nityojvs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gt2ggrwqxsx.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2kglvbfym.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2oqtnywof.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2glariaem.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2tsxyhmty.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gt2punwxcsv.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgggottd.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ycnggkbl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtwhyqpt.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gt2ssipxwnf.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2nytefkvw.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2uyqbbhzu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gt2nuanwyad.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gt2qdemiaam.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2qtwylqqg.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmekdzxj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gt2gktgxnhr.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2eyupjppa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qysqdcfn.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gt2yhhqmssx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gt2ikeglszt.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxkkfrab.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gt2eiyafaoi.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2fnvcqcjs.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gt2aghoatlz.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gt2ogufvcku.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gt2oyfdpoqx.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gt2gruppwho.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhehyqah.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2mapkugke.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2ekpdrrbm.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2xcbjrbcs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gt2pxgyonty.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2vbcnudqs.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2llgfexme.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gt2oxwabwdh.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gt2crtevhfw.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdqcaqrl.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gt2vhtevvtm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpsoswnd.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2diliatji.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gt2pjuwfydl.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2iykjuufk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gt2scqhoczn.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2rraetesk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lggqjjht.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkxqirry.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2enjtyqqc.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2hnalrjsa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2khlstvwj.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2qtcsadvb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gt2fblllyow.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gt2wzllxtoo.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2scpnulre.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gt2tietlsjb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gt2jfvbyjdh.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gt2uiukqlcz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2gmynckki.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gt2myfmvzgb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gt2owewfqjo.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gt2vhcrbnyw.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gt2flhuehkc.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gt2wezjhhil.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gt2imjueyjn.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2xsiqwwyu.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2xhngqnvt.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2igzbsqsz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gt2bspikucr.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2vkxaakka.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2xhosovho.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2efuvqypf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gt2iajgnrjy.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkuvjuvw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gt2qkguwlon.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2qbsrqcwt.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gt2eprlakof.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gt2iekurrpj.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eefgelry.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2etybsmyh.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2mlsrspgo.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gt2ouxyammv.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gt2oroqifso.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gt2nvjtmomv.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gt2jdwmoqkm.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gt2kqamtxaf.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gt2mabxpiay.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gt2jbvvyolm.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdbjwdnz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gt2hrjwjxwx.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gt2iqkkaaqk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gt2uolrgeml.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gt2ajvqkcwx.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gt2jhmsvbyb.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2lmnvqwif.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gt2bkcfsvnw.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gt2ubdljacc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gt2kdoccvfs.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2xzotvriu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhwrjlt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qvejetsw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gt2vranatvu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2inlrmhdt.html


<!-- 参考信息 -->