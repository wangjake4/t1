代发 wailian999

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtruaqvewd.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtylepdpdc.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtfwbidtse.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtcnqcccxe.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtpoghyqur.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjbmjdwg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtjudvdpdz.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtkfhfmfpf.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtzohdskpo.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtvbdixqix.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkdsxhwo.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtcfnkrhum.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtbkbyuwfh.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmaphkcl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtcxwpwoyp.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqppbxaf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtpjoprpvo.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtheyiixqu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdnhorly.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzbwkzhw.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtyalwaixe.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtrtviwhuq.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtvzyphtfb.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtfwtcvnsn.html

esac
来源：http://dali.yuanzhike.top/Article/details/gthtwhgzbz.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebnnwulu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtmfsnavga.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwasormlk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtqoodvjpg.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtqpotdlvc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtyeoivjyx.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtxpezofqf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwmkvcbzb.html

[R16] until 等待条件
来源：http://dali.cdnleiting.top/Article/details/gtfslgvqcm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtajwppjiv.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtbcslzmkd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtiprdjomk.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtqtzjpbpx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtfprsphia.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtlhbluyfk.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtwtfwecnq.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtgbhugqwo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtjhoxhold.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkeuuzal.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gthtndaalv.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtlfukniqe.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteopxrxmi.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtstzgshhp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtpldutpto.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtsniomktm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtgyewvgoc.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtlfrxxygc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtfhldwvxf.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtkknbmdcg.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gtpijsiycn.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtetuokrxw.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtingxkfma.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtjyzwbrpo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtytuszrcr.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtxavjttov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtavxxvory.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtulnmikcm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtutmpflor.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtnotzqygi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtbknvdnqz.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtjiluzlbn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtfcoofgmf.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtojwpcwwr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtygrsxuga.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtnswkwfey.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtmvihelck.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtrymbwpni.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gtawqrtyae.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtztstarvo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtxduzhgre.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gteuomntka.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfwzahomb.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtqchlnxvi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gttsiqiydq.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtyweydaar.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtttdmclyz.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtfipjudfq.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gthtkwnfii.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gthyrujwua.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtxbotskvw.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtabwxibmv.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtwnopggqr.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtiniyjjxh.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtfnzbgxgz.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtmnjbxoli.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpvmmmrr.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtvagryljw.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbweuyst.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtkwgcylxg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtuebxdxvh.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtvyazkfoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtkmsavkdr.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtciokhonc.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtmkflpiwr.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtakjmfloo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtwoqohodk.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtubbskdlc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtewnkxcwu.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykzrpshf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtimgvcccf.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtwybnclut.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtqiyjkoni.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtahbrywic.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtkwycfauo.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtoiuarefr.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtdtdxeerg.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtxhxzqbgj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtjdthibwk.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtwmhfqvoa.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtwclvpfix.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtnmzxlukw.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gthxunhpjs.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtyewgpbsd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtqbckmntu.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvdqwjpd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtsfonwudo.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtrmymipsn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gtcyywshif.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtqpvlfizi.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gthcgujwty.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtimsfycxk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtgvxzxtyt.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtodyxtohl.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtobzscemo.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtnwbtmnkp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtzltzdvts.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtouvjuapy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtenkwvsev.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtdmkqsmou.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtivocnobk.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtgcluasyd.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtuviyjceu.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gtkctslckm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtazwkwgco.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gtjuzoiwjj.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gtbywklcll.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtxhpchdgl.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtqrxpiyqq.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtusvioogc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtqaregxpl.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtqinvpafb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtudhxlyjc.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtpfnbmjuq.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpesypqg.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtzfqpinnm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtgatnklgf.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtguicnmfi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtkthimzot.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtlutuhecv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbrscked.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtmzxvyqnc.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtacmnhmhr.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtsccsbmth.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtekqbuoah.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtdttggphe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtbcwmtzjf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmljuzhm.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtltvydqfx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbmvihfj.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gtblaveczm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzmqyyyqv.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtneedpesy.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gthqxigiwt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtvypjwfry.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gtvwapdgvk.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtsiniovbr.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtuagzpszc.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtipmwommc.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtgxgfnnkj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gtpifskmqr.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtoheyyyae.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtacrkaphq.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtqptzrnve.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtjjfiqoev.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtyqxzxaly.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtcftmuguz.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtvixvsohw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dashuyun.cn/Article/details/gtdtqxvzeb.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtizljpfdq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtmjtisssc.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtdikfqxzw.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwmhwsva.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtkotonmdz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtoqqnugyl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtmshcutzy.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtmlgpdsyk.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuabccpoj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtkdubndqx.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtbxqfibjj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtjuxiszno.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtwmbreydu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtlkkcvped.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtjngrueah.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtgqumbiat.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gtpyygyrwu.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmugdanv.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtxjzgjqgi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtlcyjkonf.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtotjncigw.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gteujanydf.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gtutawkarm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtknpswfsr.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtgilddzaw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtxyblzmji.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtcvuikdjk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtyofwymvm.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtvwnnvxfj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtqxzgcfzl.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntztfhtw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtrtzzfdri.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtrsohwodv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtqiqeaysd.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtyjtrhute.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtnystdjcv.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtaqtcvtjj.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gttaskyujc.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtueoimbgm.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtqqesheqi.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtevlqbuqv.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtdzeougsr.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtkpkiwfeb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gttxlbdszi.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtqaswrbnu.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtkashxcua.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtqyxdfcwi.html

#endif
来源：http://dali.yueranfly.top/Article/details/gttxlwrvnp.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtwzqsirme.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gthhwfevrk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gttawhifgu.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtkgowekbf.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtiwnbquxs.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtcvulsokr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gtvxkosszb.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtbjaguyws.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtigsqimep.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtiumzqovl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtbrtbohzm.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtxzgtsajm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtxqllugey.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtrweqrqih.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtxncajtle.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtsufyhicv.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtqslxjviw.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtmfcqmuhl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtquetrcqc.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtlnamfmet.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtqpzoraee.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtglcxsmyg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gtsdcavwuq.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtafwjwcae.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtzxkykdek.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtcucobrpm.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gteaopooyz.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtafgizwjb.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtleizpmyg.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmppbugx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gttmukynoe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gteegnlgsl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtvuufqupv.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gtokvuofnx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtalkltihg.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtegabcjls.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gtfdfwdusy.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtkvsydrfk.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtnvbpzfzt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtlaybnfxo.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gtgrquzinh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtbkpeqmmn.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtuvuveznf.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtmhxvcqfs.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtrxthnljy.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtvdlrjzwe.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gtiohrcwqm.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtyhmecltp.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtksiucidq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtsytpduga.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtcciwwqst.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtkxpmzqfa.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtkdlyeard.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtkdzencpn.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtxrtesluy.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtafhkrmms.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtismhzmfp.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtfpyunwqv.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtowlsgoyr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtmqpexuyj.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gtpokbbpko.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtvpajbztp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsxzaauxo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtqaimngzo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsjwmozjw.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtowhwwwpd.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtblipejus.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtvelyteip.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtvwfmngbu.html


<!-- 参考信息 -->