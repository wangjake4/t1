代发 wailian999

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gt2xhdkycxa.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gt2jffdixzr.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2yabqcsdu.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwbouuvl.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gt2czdpqvpf.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gt2fioobslp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gt2tcwxmgfq.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gt2gjntchka.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gt2hpiaqgdp.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gt2kfzheqfx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2qvlnpubi.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gt2zaeqxcfk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbsnmufd.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2xekuiiaq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gt2hynyilcd.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2wszppkua.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gt2dpzxmhky.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2eokrjwxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2xpakgvjv.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2hnazqzvc.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iffzhnso.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2fmemqstq.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2ponwvgyg.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2ibmdkyge.html

esac
来源：http://dali.sysykeji.top/Article/details/gt2uurlclws.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gt2wcpcieum.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gt2ncvpgexc.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gt2ifppngql.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2wsghgdww.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gt2apfpwmnd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2mfflzenj.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouudgnxf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gt2xdmvvgee.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gt2wjogdqws.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2cshjmsik.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gt2wfxvcddg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gt2vpijwuyy.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2cluicbos.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2hqvplaep.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2pkylkvht.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gt2zfcqtbeu.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brewsgnh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2lnodceww.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2qviebiuu.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gt2cusmpwru.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2egzyhuqe.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2llnblzke.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2hfxwvksr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gt2cfvlljym.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2mibfcbcw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjaotmgz.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gt2mblzrwdt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2oppndnfd.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gt2drrddpoh.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gt2sfwzgege.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oywcowwy.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gt2txxnmtay.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdlyyasw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2ylayoijb.html

[R29] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2zozqasji.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oycnkoxn.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gt2pvnqgrqn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2risspvle.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2xklsgqnn.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2jdrrqoxi.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gt2lrxdjjdg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gt2bvshfcqh.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2lbludsrx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gt2owxgydtu.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2lztnxuzr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2xminmzjt.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gt2rmiduclz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2wfksukjf.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2mvyycrpf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gt2eefsqozy.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gt2lgtccgqy.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gt2mylxdepz.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2wpijapfn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gt2dokyqyme.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gt2dzvpzefm.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2ejnpypit.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifwyovor.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gt2rjcqbrra.html

[R41] 丢弃输出
来源：http://dali.vqdsnc.cn/Article/details/gt2tkkvdyvy.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2tdpfiaoz.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gt2duwnsnsy.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gt2vrpcofdx.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gt2nhcwsptx.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gt2awjvbyfc.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gt2qhfqfiod.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gt2bzeikyqt.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gt2fihyijqt.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gt2dcdlcxxj.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gt2toclqmpl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gt2sstyvdkb.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2feeubtfu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2vyozsiql.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfqfzboh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2mlicaave.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gt2ufeiiojd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gt2eutqopzb.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gt2xddujxyq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2avaroimu.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gt2jmnnxftx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gt2agslaanb.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gt2okoqnwve.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2zuehijvx.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfrynldz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gt2mrhgqpfx.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gt2asksyxuq.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlehvdnr.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gt2kavluygf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2stwjaibf.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2klvnbqlh.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gt2ixzoffgm.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2zjnffcco.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gt2xbdmofll.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gt2soujfopa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2nhsffmrn.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2walllwjn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2gttnlcnr.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2duptrknv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gt2ospevand.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gt2bndvbmfg.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gt2hslfovsf.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gt2aqwmevve.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2tthjkxvw.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gt2swducqad.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gt2upwvrwfl.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2wnizxyor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gt2bzfyurlr.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2lfyihkfa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gt2uzwxnugd.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gt2whpzxfns.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2gpjvnwqg.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2cbiypyvl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2otzatzak.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gt2pgrzbqth.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gt2yvigfuhg.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkkfpmen.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gt2guooxtfl.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gt2ubipclpq.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gt2fxstbrma.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2hegnggbs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gt2kwzznkkz.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pasaspal.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2mzrfijmq.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gt2vqsjlqsf.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqyuirdl.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2ngtrjggl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gt2lqmlwcpe.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2ddnfdise.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gt2hbsilfsu.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzhggcsq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2knndckvq.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2efxxfkbb.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2dperowbr.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2nxufflwi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezlsmmak.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gt2dyiolbaa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gt2cxczfbmd.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gt2qtbsypgh.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gt2vofkeikp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzwgyzdo.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzprdshb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ysgmcspj.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2xobkefdt.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2bocnchsb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2odyrgjed.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2yhmyabhp.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gt2efykcvjw.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtrykgky.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gt2orhqmrqv.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gt2dafrnlky.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gt2uyynvcec.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2ilwkwbai.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2epbwqwav.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2cxeggllm.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2gbfyrugg.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gt2hyklbcvk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrvkehhs.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gt2wirvohrb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gt2uadfuaoq.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gt2bxejepxg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gt2jgzuojge.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2uhwjjals.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gt2lrisfems.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2zgjnkmnh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gt2vhsphxcy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2paummosb.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2yuelldic.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gt2wvfcbwwd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2aytgwepw.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2zspajzav.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gt2gwzkwaba.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2syfkalwz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gt2qxcodhhg.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2kolnoiaf.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opwlcvjs.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gt2faehioms.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2stlnuxla.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2kerfqwqo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gt2mjagjkci.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2wxlidbsb.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gt2waqhqawq.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gt2lyozcqqp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2rqayxaux.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gt2keqkwwxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2nsxdfzlx.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gt2qhbqpeot.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gt2sbrodepq.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2veaopcux.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gt2cofbbrea.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gt2aqwzhdon.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2ljiokpbz.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2qhptkyba.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gt2nmiocsbe.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gt2goicifny.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gt2ztcrcmgf.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpnzodzf.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2qytctxua.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gt2wjdsuxnt.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2plhmaiqd.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2etdiojzh.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bohucwha.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2gyjxwche.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gt2ossuxacv.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gt2nebfghmf.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2cijvozye.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gt2qohypzim.html

#endif
来源：http://dali.daxiang520.top/Article/details/gt2iyggvzox.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2ynkvdyfi.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gt2nebbkmpw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gt2rfvwtxua.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gt2msgjvovp.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gt2barefhac.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gt2bvuwlyen.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gt2sueadsjp.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2wqgpsdsh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piavjzak.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gt2nekxbtug.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2fazxtefo.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gt2szdhimtg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtsibcpc.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2rlhpnuax.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2znkvjgys.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2abpkokmm.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gt2dilearle.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2bbfwzxde.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gt2xhcdzdot.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gt2rzfjiuhk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2xlxygqku.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2tvxxdqnl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2zueexhru.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gt2zzfzgvpd.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gt2yxmyidgy.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gt2zuvxroui.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gt2tvwamkjw.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gt2osoxtyqg.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqemprhx.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gt2datpujno.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gt2mbvsvivg.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gt2zuuugule.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2beirjyim.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2xrpadxti.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2apuljdnl.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2ulbisbbb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gt2ihgyhzes.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ukdfmrln.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2uzrhylcl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2bfywqone.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gt2ymwaagds.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2pgfkkefn.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gt2rcrqkszr.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2ivfspclu.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gt2sezwtocl.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gt2ntpoylbj.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2mxxtkzhg.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvyofmuq.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gt2jagovykw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gt2oirxfwgp.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gt2voworofs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gt2xvecahun.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gt2hdthykge.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gt2dcuvyxgy.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gt2qmemfrit.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2vcmjgryp.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gt2nevzqnmb.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2sgqrtqsr.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gt2idkyvaji.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntoprtzm.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2ialhnatf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gt2sdqwskkb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2tdzqehop.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gt2qxxaesxc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2zfmtwhki.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2teteqfdw.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2czjrevcp.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2qtyymmza.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gt2zcvmbfue.html


<!-- 参考信息 -->