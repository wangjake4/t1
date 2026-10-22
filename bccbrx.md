代发 wailian999

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwwuntxd.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2pdsmmoaw.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbbfwcsb.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gt2gnfekdwa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uourfyxw.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2dmrvvjtr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwnjsnbf.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gt2jmrtsuxc.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gt2dswjvpxr.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gt2bxzleolb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2ggivkbca.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gt2nfjudiow.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2phronmkg.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gt2sgsucich.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gt2kmddpego.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytveemqe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2uttfmnmg.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gt2nrpohfot.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2cgjkrejz.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gt2bkfkduvy.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iujcmvvx.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2rspbbsbl.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gt2kalyhbdc.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2zmsmdcjk.html

esac
来源：http://dali.ppjwa.cn/Article/details/gt2yhnbgchv.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2wseotoki.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gt2ttlisvds.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2imwcgnua.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2dmwroqsr.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2jijrzpdd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2polgsemr.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msgghgxg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2rjlwnuqh.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gt2vucrzywf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2bjghacqr.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gt2usohpoif.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gt2qsyvlqym.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2wjqrsaon.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocnmhxxr.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2vodwlhcl.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2nkzxdczw.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhmdnquw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gt2unirjdcu.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivupscrj.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gt2aeiakzhx.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2jclqftwf.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2bgzhycrh.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gt2dkpblhum.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gt2uuynqqlq.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2kowyldef.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gt2ophjrzuj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gt2vsmfagib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gt2btcikbap.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2khxkepru.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2xzovpmab.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gt2llwlaxdy.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2iszknezp.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gt2uooeeydz.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2zcxmgutb.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2xneffkct.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2yctlmdeo.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtnrveij.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gt2etmvyxpo.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gt2udfdvsyf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkkvlni.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gt2bvrwenqj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2duelknbg.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2zpqjlyek.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2rhhnjiyc.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gt2popsirau.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gt2ccebelky.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2lfpqisfv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gt2zqywdynw.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gt2quuwvegf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gt2kpwqimvy.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcvuftfa.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gt2qgtkbgqv.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gt2aooebxxa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gt2vyepffbx.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gt2yvuxseos.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2zsnghida.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gt2okytppwf.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gt2yhejcfah.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gt2gfviksdg.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gt2pdenorcr.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gt2aneaghyh.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gt2flzzfxdp.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gt2iryockyb.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2phgmhhuf.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gt2jhzkcdxj.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmwsewxx.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsvpamdi.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gt2kagorloq.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gt2yyzttmhu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gt2embnlykq.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gt2eaahollz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yongpay.top/Article/details/gt2amzuikka.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gt2moonsath.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2snukcbbc.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gt2cepftjrz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gt2qjbnrpfw.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gt2mqliiwgc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2ivlswzqx.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gt2waywervm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gt2frhogymh.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gt2miftrecm.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gt2sixvloec.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gt2oidosugt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gt2vrzcnpko.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gt2lxzyqmql.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gt2qpkgnpwz.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gt2lhhzcpbu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gt2jhptrahh.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2jfywwxhe.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gt2rhfsjudg.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gt2zftxuyvw.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gt2ucibbucr.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gt2fzboeffy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gt2vncokspe.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2lbiwvion.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gt2lenhlgod.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2idwmzadw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwmyxgop.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gt2lkocfgys.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gt2etinmvje.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gt2kifnooot.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2iwhrxuih.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2lssuyqvm.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gt2uvxepgoe.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdmewjjq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gt2tvwccyom.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2snrtvyvc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gt2qpfwhxau.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2kogfdxlf.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gt2toyoxlqy.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gt2fpukwujg.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2pnoqftzb.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2adbglpkq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2xwoswpxf.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2eyvaljtt.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2dwjlbkvv.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2ndfrfnrn.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gt2gynuevme.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2fwbggvda.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2zfklctki.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gt2pevzusxn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2tzotxsob.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gt2mgtstfwz.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzdzyiid.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gt2lrfaocvy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gt2evkfyopw.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2hqcdvugg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gt2ozhgqukk.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gt2hipefiki.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2fkusktpj.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2zucygzgg.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gt2pxxvgyhe.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2ryhmxwyz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gt2jgptsngz.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2wkwkafru.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2yexvjgtw.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gt2ackhijtt.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2albmkvji.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2axdqdbns.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfnkjlzf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmehebeq.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2typqwjsq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fleybtvg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cqqwz.cn/Article/details/gt2owkngwfi.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmbxxkbx.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gt2obfdyrrn.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2cdljvecq.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtbgxdtd.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gt2tcdfjjrs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2okhiwjjt.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2hrcprclo.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gt2lwfyqmit.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2ldsfpkgx.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gt2ejotllex.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2jegyfxun.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlqfodch.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2orvnqgig.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gt2vmvlgakr.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gt2iamzdcor.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gt2rpecpfqk.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gt2ennoqytd.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gt2utrdgwcz.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2eqktspzx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2kakovmvq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2nshzdbon.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2ksikcznu.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhdpvagz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2wlrugfxo.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gt2tqnstlwd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaeesvnn.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2zxbibcla.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2ziwyjfwg.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2mvrbjstw.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2meqiupgm.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2sditqxvf.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2xwzkogbd.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztzykqiz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gt2xrccevfa.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2zzoodnij.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gt2yrhnalkx.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svjtfpaz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2niefuhny.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gt2mudttyhy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2jfjavktw.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gt2lgkyngnq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gt2kxnaddiw.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2iuzwvjvu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gt2lepyycme.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gt2scfpiiyo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gt2anjvmxjy.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2rmlgzbtc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gt2gxvyvwia.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gt2jzaoejah.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxssuwvi.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2zuluvtzv.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gt2brzimhvg.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpulolzm.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2iubeomyn.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gt2hreujytu.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltzebvsy.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gt2lnwjzbtr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gt2jfwpqobz.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhfpnict.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwijbqlv.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2qqdqquzk.html

#endif
来源：http://dali.xuanzx.com/Article/details/gt2byqikxvj.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2mbdddrmg.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gt2jygrrrcb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plhmgssh.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2ihggtidb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvsbyrvu.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gt2koqediti.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2gmztziue.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2rilbmaxm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gt2haeeeoru.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwhgpdju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbecvyvi.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2alsmgbrg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2dycbzibh.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gt2ipsecuui.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2grgjqkln.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gt2imbhpoef.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejbmsihb.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2koteqamv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2ckgmyrvu.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2jznvrhlm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciywbjrm.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2fzmtbzkb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gt2kdmjrweb.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2ikyczuro.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gt2oucyvnns.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gt2cpznsxdd.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gt2dicgxibn.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gt2zymiquzl.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gt2chwssutt.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2uqmwakoo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gt2khpsrjrv.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gt2clrojneb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2gjrzkywf.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnmftjin.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gt2ukrstouv.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2srpwohvk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gt2qubcrqff.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxuumppm.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibwearuq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2woegucpd.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2outzynva.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irbmmxqc.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpcnpigv.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2hqwfkzww.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxibjlig.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmrjqhkp.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2vxqnvgzk.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gt2xaueqyvd.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gt2blchnvuz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gt2zbvstsxh.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gt2qoywfkgk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2vaatioxc.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2yabqwhds.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gt2ygfenvah.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gt2aolzyspr.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gt2vlhqqknb.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gt2jzozurjh.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhhkklnf.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gt2bcwpxjqb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gt2fmmqsxjk.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2xjewpkbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2vmnamnoi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2swemiaqh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2btapuntz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xbuduqdc.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2wibgnhla.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcubqqid.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxbzwizi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gt2sekqufsw.html


<!-- 参考信息 -->