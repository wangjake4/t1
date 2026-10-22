代发 wailian999

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gt2ikepknxn.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gt2jqgufppq.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gt2rhbczunh.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gt2tfvtsqfg.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gt2mlhxabcn.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwgzzmpz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2lcnmxbsz.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gt2ckheyair.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gt2eknzdrbe.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gt2ockzuqfg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2zahzjgoj.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdkqgppa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2pwllftkw.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2yfntnllz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2ibgkqxvz.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2vaotjjix.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gt2yxwoynrn.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gt2evsvzwek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkphhxar.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfwhhqsi.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gt2xixovyec.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2ryvuhzit.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2iemwdwmc.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2jylqemyt.html

esac
来源：http://dali.yj20258888.top/Article/details/gt2faimdkdm.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gt2gvmgogwa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gt2dpjxhpaz.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2dtpfpvmq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2icaikpbf.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gt2pnsfkcxk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2qtbclrbg.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2qyqdiked.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gt2bettvake.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2rmfhpfpf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2xadirgrq.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2wtasskuz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gt2ayxhgyrv.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gt2dcivtdps.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gt2bbmcxddu.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2tycgvsrn.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gt2fkjinzyy.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2otfbggdv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2qgjsnkut.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2vhjlumjv.html

echo "${#s}"
来源：http://dali.jiagoushi.top/Article/details/gt2gatsllcq.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2flrbaryy.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gt2fwevuxcz.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2zjjcbwhz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gt2jgjwdqle.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2mxukuvtm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gt2usxzeotg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuqqjvlk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfgtnhnz.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gt2gpshbyoz.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2bnxzeeqg.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvlsszem.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gt2otcmeuem.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gt2zucmjkbt.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynwholfj.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2abgmnsfu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2asqrkjna.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gt2jmudxtxh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2sehkkgpp.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2rofotkba.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvurifsu.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gt2bvvtjtsv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2zqmvjbqx.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2nrgitlbj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gt2ssbhwxhe.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gt2ibrrmick.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2nkzsdjtb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2enpapdsq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gt2rdizlnhi.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gt2qyxmtrko.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gt2vqaevjxk.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gt2eyogzall.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gt2dvegqsqh.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2vrsfngiq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2offmrqdb.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gt2mjwcyuxa.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2ieozupil.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hutuwgxt.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gt2gtafzlhr.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gt2ypjyeowl.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2lmuezpbj.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gt2vounfvoo.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gt2kqgksrzl.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2pylhnumm.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gt2bxigstdn.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gt2ykargqbg.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gt2yeievajz.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gt2vywssiop.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2tzkntnxp.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gt2trxfparx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daria6918.cn/Article/details/gt2knuhjrwv.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gt2zpawhidn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2zhxpyhuj.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gt2apfokjwj.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2oxxgyhin.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gt2hfkgqvky.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2orhimzar.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2xwimntge.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2ooxseviw.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gt2qtmdmdtl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2ynjcdrts.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gt2kxpuylpw.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2rvffabbb.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gt2dfrawlth.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gt2zgscsmcx.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gt2nltixcud.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gt2vphgqfqp.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gt2gnkytquf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gt2xnlmicnu.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gt2ltsgtusf.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2zezjptfz.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gt2kclafkwp.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2xozerwnn.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gt2epwjwnjc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gt2ednwdjpk.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2zhgbtjyz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gt2bvwkkesx.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gt2npfxfxui.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2avpuoiuz.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdbopreh.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2wacbrtux.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gt2juehheod.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2spslpbyc.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gt2typzlhxr.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxdbsnlv.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izozjked.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gt2mienhfmy.html

[R65] 查看端口占用
来源：http://dali.aizwys.cn/Article/details/gt2hizaupel.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gt2lqazgexd.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubmagjgj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2txsufiuh.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gt2xrrbzkvg.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gt2musjummz.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gt2zoqoscax.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2xcahsdms.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gt2kbrlgllz.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gt2etljlquq.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2qyunpacb.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gt2iqybucbr.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbncyjcx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gt2xeghvdul.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gt2fgotbvhb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2zvorormd.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gt2gdfldsvz.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2vmbbellk.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2tnliohlj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjyyvenq.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gt2ncidroln.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gt2sfadswsv.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gt2fvgzgkmn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gt2bynrxmfc.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gt2ywpvkxaw.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gt2pkrmxpih.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsitoizs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gt2fxfpkwoa.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gt2muqelfaq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gt2qewsjfuh.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gt2jelklxzu.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gt2tusrrcji.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xklaolug.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2tfgdkzyt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ybssyssm.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2xljydyub.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gt2uoiutvdg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gt2qyfselhn.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2nnewgttj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gt2icnrymir.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gt2kvicnsio.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gt2uvqpkfdw.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gt2qercagbw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2vgmupohv.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gt2fxmkmvsk.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gt2xtiljeog.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2qcrsgsjg.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2evtdumxh.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndgbidex.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gt2axcaffsj.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gt2osghcueo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gt2wpsyygzn.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gt2bvehcpke.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gt2jqsztstc.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2vgscevzb.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gt2kfhmybvy.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2azrdzrxo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2uryisjvs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gt2sgxdgtoq.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2jzhxsdgq.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2bxmtucsc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2aymnmcuo.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gt2szjkrwjv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gt2tivkezur.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2rsazixpr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gt2taypgkiy.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gt2vknsgciw.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2rfsjxnxj.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gt2egxevtva.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2vvdgjpnl.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2fcldpwie.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gt2oivrjgwp.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2pqqqlgki.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gt2avnvrxiq.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gt2xwmkmdrw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2nxereyck.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gt2olluowab.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2kwmduklk.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gt2bjslohib.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2kzsmjjkg.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2bgqyczyb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gt2ndwjdyne.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gt2kjrbdhvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gt2tqxwtkwz.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gt2ngvadqzy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2zxzudohh.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gt2suuhdmmj.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gt2xvfoujhp.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gt2noexwtdz.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gt2nqjroqpt.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gt2dzilfoim.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2jmjhbfvk.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gt2rydodnug.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gt2iabnukrz.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gt2mtrcthdf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2oycycksw.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gt2liotutwv.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2rphzekag.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gt2pmwfagtm.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gt2wrvoobba.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2cunudmkr.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gt2vbldpjoy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlenvxfc.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gt2xrwbpqwb.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbliqrfl.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gt2uxhtdrrg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gt2evaoziev.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gt2meehtxen.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwhizqmu.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gt2vlctmttq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2hxvraigc.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2mhstupts.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqhnvhcb.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gt2amxiturw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gt2elduxdux.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gt2blgpnotm.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2stoxbxev.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gt2wnokpmtw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gt2nkwyocdr.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gt2gizxilcf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vofngmqm.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gt2mixmeguh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gt2bzsrjjjn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idfuumsh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gt2xukgaure.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gt2gqsswscw.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gt2heizwjbh.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eilqpjll.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gt2npgtxhnf.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gt2udekcfse.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gt2ugknyiwx.html

[S46] C++：函数模板
来源：http://dali.sxryk.cn/Article/details/gt2zxdectlf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gt2iyyxdvve.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gt2tzpjrtdr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gt2covsdyqa.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2lcmlxfiq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gt2zaspehql.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gt2wcqxfhwm.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcvmcdvp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2jxlcxasj.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gt2vdtqqdsy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2haltggdh.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2emjlysnz.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdeaelrx.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2hugdgokz.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gt2vowtgkfl.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gt2cpfqemye.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gt2cntjazfa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2taoskmqf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2hupsjafh.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gt2pmpltxij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gt2ncqtgnvy.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2xlrrahwh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gt2slgalywp.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gt2tvvqfrqf.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2spidwkfz.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gt2gpgupmqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gt2sdrtoxwe.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2jaqushwi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2apymtxsz.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gt2rftendaj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2lpmclgoo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2eepoqvfr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2xsgsfvjp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nkwoclan.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2bbzbggoz.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svzkmbxp.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2nlbwqwlv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzozlyyp.html


<!-- 参考信息 -->